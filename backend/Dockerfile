FROM openjdk:11.0.4-jre
COPY backend.jar /app.jar
COPY sample.db /sample.db
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]
