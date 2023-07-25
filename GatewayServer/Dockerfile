#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim as build

#Information around who maintains the image
MAINTAINER sovansingh.com

# Add the application's jar to the container
COPY target/GatewayServer-1.0.jar GatewayServer-1.0.jar

#execute the application
ENTRYPOINT ["java","-jar","/GatewayServer-1.0.jar"]