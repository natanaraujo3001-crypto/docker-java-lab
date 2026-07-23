FROM ubuntu:24.04

RUN apt update &&\
    apt install -y\
    openjdk-21-jdk\
    curl\
    vim\
    net-tools

WORKDIR /app

COPY . .

CMD ("java","-jar","app.jar")