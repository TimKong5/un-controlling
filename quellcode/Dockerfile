FROM openjdk:8-jdk-alpine
ADD /target/rating-rater-0.48.0-SNAPSHOT-exec.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]