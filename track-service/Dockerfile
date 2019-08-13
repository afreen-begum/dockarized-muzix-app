FROM openjdk:11
ADD ./target/track-service-0.0.1-SNAPSHOT.jar /target/track-service-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","target/track-service-0.0.1-SNAPSHOT.jar"]