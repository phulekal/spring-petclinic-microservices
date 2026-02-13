FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-admin-server-4.0.1.jar app.jar
EXPOSE 8887
ENTRYPOINT ["java", "-jar", "app.jar"]