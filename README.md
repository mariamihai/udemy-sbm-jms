# Udemy - Spring Boot Microservices - JMS Messaging project
## Description
The current project is part of the "Spring Boot Microservices with Spring Cloud" [Udemy course](https://www.udemy.com/course/spring-boot-microservices-with-spring-cloud-beginner-to-guru/). 

This is an initial project about JMS Messaging that will be expanded for the microservices that are constructed in the course.

An overview of all the projects involved can be found [here](https://github.com/mariamihai/udemy-sbm-overview).

## Docker image
For the project, I am using an ActiveMQ Artemis image. 
Check the docker project [here](https://github.com/vromero/activemq-artemis-docker/blob/master/README.md).

Creating the container:
```
docker run -it --rm -p 8161:8161 -p 61616:61616 vromero/activemq-artemis
```

| Property | Value | 
| --------| -----|
| username | artemis |
| password | simetraehcapa | 
