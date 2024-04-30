FROM openjdk:19

WORKDIR /app

COPY ./build/libs/products-api-0.0.1-SNAPSHOT.jar /app/products-api.jar

EXPOSE 8080

CMD ["java", "-jar", "products-api.jar"]
