Microservice with Spring boot and Docker

One Paragraph of project description goes here

Prerequisites

you should install Java >=8 and Docker

Installing

git clone https://github.com/joserafael872/Eureka-server.git

mvnw clean package

docker build -t Eureka-server .

docker run -d -p 8761:8761 Eureka-server

Description

Eureka Server.

Versioning

0.0.1

Last modification date:

22/04/2020 by Deployment José Rafael
