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