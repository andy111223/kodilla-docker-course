FROM openjdk:19

ARG JAR_FILE

COPY ${JAR_FILE} app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
