download docker

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
https://hub.docker.com/

```
docker run <username>/<imagename>
```
eg. vim and copy the image to mongo.yaml
```
docker-compose -f mongo.yaml up 
```

```
docker-compose down --rmi all
```
https://hub.docker.com/
