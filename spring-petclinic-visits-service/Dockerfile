FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-visits-service-4.0.1.jar app.jar
EXPOSE 8894
ENTRYPOINT ["java", "-jar", "app.jar"]