\# Container Concepts



\## Container Images \& Layers



\### Pull image

docker pull ubuntu



\### List images

docker images



\---



\## Create Container



docker run -it ubuntu



\---



\## Docker Object Types



\### Container

docker ps

docker ps -a



\### Stop container

docker stop <container\_id>



\### Remove container

docker rm <container\_id>



\---



\## Volume



\### Create volume

docker volume create myvolume



\### List volumes

docker volume ls



\---



\## Docker Layering



\### Check image layers

docker history ubuntu

