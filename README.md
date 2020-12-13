# spring-demo-parent
Spring demo parent

This example app of setting up a microservices system using Spring Cloud, it is not just a Spring boot application).

## Auth -  Custom Authorization Server, generates token and store it.
    usage:
            https://z77-auth.herokuapp.com/oauth/token?grant_type=password&username=admin&password=123456
            Client credentials : Username: test | pass: test
            
## Discovery - it is Eureka Server, server for connection of all microservices. 
               lib used - implementation 'org.springframework.cloud:spring-cloud-starter-netflix-eureka-server'

## Gateway - Main endpoint for all clients, gateway routes all requests to required microservices
