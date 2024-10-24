FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/registry-0.0.1-SNAPSHOT.jar /app/registry.jar

EXPOSE 8761

ENTRYPOINT ["java", "-jar", "/app/registry.jar"]
