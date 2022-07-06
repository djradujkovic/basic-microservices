FROM --platform=linux/amd64 maven:3-jdk-8 AS build

RUN apt-get update
RUN apt-get install git

RUN git clone https://github.com/kkenan/basic-microservices

WORKDIR /basic-microservices/spring-boot-app

RUN mvn clean package