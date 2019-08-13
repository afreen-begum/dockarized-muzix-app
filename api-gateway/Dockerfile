FROM openjdk:11
ADD ./target/apigateway-0.0.1-SNAPSHOT.jar /usr/src/api-gateway-pattern-0.0.1-SNAPSHOT.jar
EXPOSE 8080
WORKDIR usr/src
ENTRYPOINT ["java","-jar","apigateway-0.0.1-SNAPSHOT.jar"]