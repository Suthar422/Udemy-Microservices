#Start with base image containing Java Runtime
FROM eclipse-temurin:26-jdk

#Information who maintains the image
LABEL maintainer="easybytes.com"

#creating docker image for the jar and copying all data in it.
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

# execute the application using the below command
ENTRYPOINT ["java","-jar","accounts-0.0.1-SNAPSHOT.jar"]
