FROM openjdk:23-jdk-slim

EXPOSE 9090

WORKDIR /app

COPY target/ExamenDAW-0.0.1-SNAPSHOT.jar app.jar

CMD [ "java", "-jar", "app.jar" ]