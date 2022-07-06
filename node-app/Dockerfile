FROM node:9.9.0-alpine

RUN apk update
RUN apk add git

RUN git clone https://github.com/kkenan/basic-microservices

WORKDIR /basic-microservices/node-app

RUN npm install