FROM openjdk:11.0.1-jre-slim-stretch
LABEL author="GT"

ARG JAR=spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar
COPY target/$JAR /app.jar
EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]