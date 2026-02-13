FROM eclipse-temurin:17
WORKDIR /app
COPY target/spring-petclinic-config-server-4.0.1.jar app.jar
EXPOSE 8888
ENTRYPOINT ["java", "-jar", "app.jar"]