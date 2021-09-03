FROM openjdk:8
ADD target/particle-docker.jar particle-docker.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "particle-docker.jar"]