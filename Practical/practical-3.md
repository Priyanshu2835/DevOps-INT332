\# Practical 3: Docker Networking



\## Aim

To understand Docker networks.



\## Questions

1\. List all networks.

2\. Create a new network.

3\. Run container in custom network.

4\. Inspect network.



\## Commands



docker network ls

docker network create mynetwork

docker run -d --network=mynetwork nginx

docker network inspect mynetwork

