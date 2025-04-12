FROM openjdk:17-jre-slim

WORKDIR /app
COPY target/core-*.jar app.jar
EXPOSE 5000
ENTRYPOINT ["java", "-jar", "app.jar"]