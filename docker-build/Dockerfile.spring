FROM openjdk:8-jre
ADD spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
