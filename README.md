spring hello world docker

### Build the docker image
``
docker build -t <tag-name> .
``
example:- docker build -t spring-boot-docker-helloworld .

### Run the docker image

``
docker run -p 8080:8080 -t spring-boot-docker-helloworld
``

### access the application
``
Since, I am using using Docker Toolbox hence,  any port I publish with docker run -p will be published on the Toolbox VM’s private IP address. 
the command "docker-machine ip" will tell you the ip address. It is frequently 192.168.99.100.

http://192.168.99.100:8080/

application will result below message

Hello spring boot docker app
``
