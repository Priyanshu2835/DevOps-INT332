\# Practical 4: Docker Storage



\## Aim

To work with volumes and bind mounts.



\## Questions

1\. Create a volume.

2\. Run container using volume.

3\. Use bind mount.

4\. Inspect volume.



\## Commands



docker volume create myvol

docker run -d -v myvol:/data nginx

docker run -d -v C:\\data:/app nginx

docker volume inspect myvol

