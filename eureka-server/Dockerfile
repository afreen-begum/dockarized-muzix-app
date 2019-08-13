FROM openjdk:11
ADD ./target/eureka-server-pattern-0.0.1-SNAPSHOT.jar /target/eureka-server-pattern-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","eureka-server-pattern-0.0.1-SNAPSHOT.jar"]