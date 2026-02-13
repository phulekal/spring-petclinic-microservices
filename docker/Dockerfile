# -------------------------------
# Single Dockerfile for all microservices
# -------------------------------
FROM openjdk:17-jdk-slim
WORKDIR /app

# Accept service name and port as build arguments
ARG SERVICE_NAME
ARG SERVICE_PORT

# Copy the JAR for the selected microservice
COPY ${SERVICE_NAME}/target/${SERVICE_NAME}-0.0.1-SNAPSHOT.jar app.jar

# Expose the correct port for the service
EXPOSE ${SERVICE_PORT}

# Run the microservice
ENTRYPOINT ["java", "-jar", "app.jar"]