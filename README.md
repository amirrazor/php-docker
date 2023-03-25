# Docker PHP Example
This is a simple PHP example with a Dockerfile that exposes port 80 and copies the PHP file to the appropriate directory inside the container.

To build the Docker image, run:

`docker build -t hello-docker .`


To create and run the container, use:

`docker run -p 8085:80 hello-docker`


Note that you can replace 8085 with any other available port number.

The PHP application can be accessed at: http://localhost:8085


