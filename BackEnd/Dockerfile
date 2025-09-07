FROM openjdk:17
EXPOSE 8087
ADD target/BackEnd-0.0.1-SNAPSHOT.jar job.jar
ENTRYPOINT ["java", "-jar", "job.jar"]