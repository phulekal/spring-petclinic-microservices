FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-discovery-server-4.0.1.jar app.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "app.jar"]