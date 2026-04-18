\# Practical 5: Docker Registry



\## Aim

To push and pull images.



\## Questions

1\. Login to Docker Hub.

2\. Tag an image.

3\. Push image.

4\. Run private registry.



\## Commands



docker login

docker tag myimage username/myimage

docker push username/myimage

docker run -d -p 5000:5000 registry:2

