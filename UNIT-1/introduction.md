\# Introduction to Containers



\## Origin of Containers

\- Containers evolved from Linux namespaces and cgroups.



\## Check system info

docker version

docker info



\---



\## Container Runtime

\- Example: containerd, runc



\### Check runtime

docker info | findstr "Runtime"



\---



\## Process Isolation \& Namespaces

\- Each container runs in isolated environment



\### List running containers

docker ps



\### Run container

docker run -it ubuntu



\---



\## Control Groups (cgroups)

\- Limit resources



\### Limit memory \& CPU

docker run -it --memory="200m" --cpus="1" ubuntu

