FROM adoptopenjdk/openjdk11:alpine-jre
WORKDIR /app
COPY target/*.jar maven_app.jar
CMD ["java ","-jar","maven_app.jar"]
