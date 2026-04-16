\# Docker Networking



\## List Networks

docker network ls



\---



\## Bridge Network



docker network inspect bridge



\---



\## Create Network



docker network create mynetwork



\---



\## Run container in network



docker run -d --network=mynetwork nginx



\---



\## Port Mapping



docker run -d -p 8080:80 nginx



\---



\## DNS inside Docker



ping <container\_name>

