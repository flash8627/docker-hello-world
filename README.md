

1.mvn clean package docker:build -e -DskipTests

[root@localhost docker-helloworld]# docker images
REPOSITORY                            TAG                 IMAGE ID            CREATED             SIZE
flash8627/docker-spring-boot          latest              17b6aab0f77a        5 minutes ago       181MB

2.docker run -p 8080:8080 -t flash8627/docker-spring-boot

3.http://docker-server-ip:8080/



