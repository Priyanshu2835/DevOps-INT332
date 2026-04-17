Practical: Deploy Apache HTTP Server using Docker

Aim



To deploy the Apache HTTP Server (httpd) using Docker and access it through a web browser.



Questions

Pull the Apache (httpd) Docker image.

Verify that the image is successfully downloaded.

Run a container named apache-web in detached mode with port mapping.

Check the list of running containers.

Access the Apache web server using a browser.

Commands



docker pull httpd

docker images

docker run -d --name apache-web -p 8081:80 httpd

docker ps



Output / Access



Open a web browser and go to:

http://localhost:8081

