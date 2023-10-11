FROM node:13-alpine
RUN addgroup app && adduser -S -G app app
USER app

WORKDIR /app
COPY packages*.json ./
RUN npm install
COPY . .

EXPOSE 3001
