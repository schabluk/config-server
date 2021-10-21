FROM openjdk:8-jdk-alpine 
WORKDIR /usr/app
COPY target/app-0.0.1-SNAPSHOT.jar ConfigServer.jar 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","ConfigServer.jar"] 
