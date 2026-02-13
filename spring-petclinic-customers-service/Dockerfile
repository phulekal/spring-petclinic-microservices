FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-customers-service-4.0.1.jar app.jar
EXPOSE 8890
ENTRYPOINT ["java", "-jar", "app.jar"]