FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-vets-service-4.0.1.jar app.jar
EXPOSE 8893
ENTRYPOINT ["java", "-jar", "app.jar"]