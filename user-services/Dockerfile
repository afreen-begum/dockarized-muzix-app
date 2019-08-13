FROM openjdk:11
ADD ./target/userservices-0.0.1-SNAPSHOT.jar /target/userservices-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","target/userservices-0.0.1-SNAPSHOT.jar"]