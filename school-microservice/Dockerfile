FROM openjdk:17-jdk-alpine
ARG JAR_NAME=app.jar
COPY ${JAR_NAME} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]