FROM eclipse-temurin:17-jre-alpine

WORKDIR /app

COPY target/*.jar app.jar

RUN adduser -D springuser
USER springuser

ENTRYPOINT ["java","-jar","app.jar"]

