FROM openjdk:17-alpine
WORKDIR /app
COPY --from=jarfile /spring-petclinic-main/target/spring-petclinic-3.0.0-SNAPSHOT.jar /app
# EXPOSE 8080
CMD ["java", "-jar", "spring-petclinic-3.0.0-SNAPSHOT.jar"]
