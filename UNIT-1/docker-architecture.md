\# Docker Architecture



\## Docker Daemon



\### Check daemon

docker info



\---



\## Docker CLI



\### Help command

docker --help



\---



\## Docker Registry



\### Login to registry

docker login



\### Pull from Docker Hub

docker pull nginx



\---



\## Workflow Commands



\### Build image

docker build -t myimage .



\### Run container

docker run -d -p 8080:80 myimage

