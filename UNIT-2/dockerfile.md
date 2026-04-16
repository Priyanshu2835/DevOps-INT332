\# Dockerfile Concepts



\## Build Context



docker build -t myapp .



\---



\## Basic Instructions Example



FROM ubuntu

WORKDIR /app

COPY . .

RUN apt update

CMD \["echo", "Hello DevOps"]



\---



\## Build Image



docker build -t myimage:v1 .



\---



\## Tag Image



docker tag myimage:v1 myimage:latest



\---



\## Inspect Image



docker inspect myimage

docker history myimage

