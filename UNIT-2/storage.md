\# Docker Storage



\## Volumes



\### Create volume

docker volume create myvol



\### Use volume

docker run -d -v myvol:/data nginx



\---



\## Bind Mount



docker run -d -v C:\\data:/app nginx



\---



\## Inspect Volume



docker volume inspect myvol

