FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-genai-service-4.0.1.jar app.jar
EXPOSE 8892
ENTRYPOINT ["java", "-jar", "app.jar"]