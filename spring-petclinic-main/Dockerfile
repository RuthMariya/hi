FROM openjdk:17-alpine
# WORKDIR /app
ARG JAR_FILE=spring-petclinic-main/target/spring-petclinic-3.0.0-SNAPSHOT.jar
ADD ${JAR_FILE} spring-petclinic-3.0.0-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/spring-petclinic-3.0.0-SNAPSHOT.jar"]
