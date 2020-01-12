# Eureka Naming Server

Code Forked from:
[Microservices with Spring Boot](https://github.com/in28minutes/spring-boot-examples/tree/master/spring-boot-basic-microservice) 
and Java - [Part 5 Tutorial](https://www.springboottutorial.com/microservices-with-spring-boot-part-5-eureka-naming-server)

Example code part of in28minutes. Added google jib for docker builds 

This part uses the Eureka Naming Server and has the microservices communicate with it.

# TL;DR
1. clone repo
2. create docker image locally : `mvn clean compile package jib:dockerBuild`
3. run docker image locally: `docker run -it -p 8761:8761 localhost/sb-ms-ensvr`

