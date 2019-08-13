FROM openjdk:11
ADD ./target/config-server-pattern-0.0.1-SNAPSHOT.jar /target/config-server-pattern-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","config-server-pattern-0.0.1-SNAPSHOT.jar"]