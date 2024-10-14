FROM openjdk:11.0.2-jre-slim

WORKDIR /app

COPY ./*.jar ./app.jar

EXPOSE 8080

CMD ["java", "-jar", "/app/app.jar"]
