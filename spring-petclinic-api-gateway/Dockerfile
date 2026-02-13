FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-api-gateway-4.0.1.jar app.jar
EXPOSE 8889
ENTRYPOINT ["java", "-jar", "app.jar"]