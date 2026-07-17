FROM eclipse-temurin:11-jdk

ARG artifact=target/spring-boot-web.jar

WORKDIR /app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]

