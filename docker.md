## docker

https://www.docker.com/products/docker-desktop/

micorsoft need open hyper v

https://learn.microsoft.com/zh-tw/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v

build docker
```
docker build -t <imagename> .
```
list docker images
```
docker image ls
```
list docker network
```
docker network ls
```
download the environment with docker hub
```
docker pull <username>/<imagename>
```
remove all container
```
docker container rm -f $(docker container ls -aq)
```
remove all images
```
docker image rm -f $(docker image ls -aq)
```
run the docker with docker hub
 - https://hub.docker.com/

```
docker run <username>/<imagename>
```
run the image name myng with nginx on port 80
```
docker run -d -p80:80 --name myng nginx
```
```
docker exec -it <link> sh
```
```
apk add curl
```
```
curl <imagename>
```
check the ip and host
```
cat /etc/hosts
```
## docker-compose
docker-compose list
```
docker-compose ps
```
docker-compose build the project
```
docker-compose build <--no-cache>
```
docker-compose start the port
```
docker-compose up -d
```
eg. vim and copy the image to mongo.yaml
```
docker-compose -f mongo.yaml up 
```
docker-compose stop the port
```
docker-compose down --rmi all
```
https://hub.docker.com/
