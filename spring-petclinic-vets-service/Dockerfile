FROM eclipse-temurin:17
WORKDIR /app
COPY target/*.jar app.jar
EXPOSE 8893
ENTRYPOINT ["java", "-jar", "app.jar"]