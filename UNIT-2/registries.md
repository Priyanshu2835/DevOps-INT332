\# Docker Registries



\## Docker Hub



\### Login

docker login



\### Push image

docker push username/myimage



\---



\## GitHub Container Registry (GHCR)



\### Login using token

docker login ghcr.io



\---



\## Private Registry



\### Run registry

docker run -d -p 5000:5000 registry:2



\---



\## Tag for private registry

docker tag myimage localhost:5000/myimage



\---



\## Push to private registry

docker push localhost:5000/myimage

