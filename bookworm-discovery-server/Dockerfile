FROM openjdk:21

EXPOSE 8761

ARG JAR_FILE=/build/libs/*.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","/app.jar"]