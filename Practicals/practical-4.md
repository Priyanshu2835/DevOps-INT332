Practical 4: Deploy Custom Web Page using Apache Docker Container

Aim



To deploy a simple web page using the Apache (httpd) Docker container and verify it using command-line tools.



Questions

Pull the official Apache (httpd) Docker image.

Run the container and map it to port 8080 on the host machine.

Create or update an HTML file inside the container with a custom message.

Verify the output using a command-line tool.

Stop and remove the container after testing.

Commands



docker pull httpd

docker run -d --name my-apache -p 8080:80 httpd

docker exec -it my-apache bash -c "echo '<h1>Hello from Docker Apache!</h1>' > /usr/local/apache2/htdocs/index.html"

curl http://localhost:8080



docker stop my-apache

docker rm my-apache

