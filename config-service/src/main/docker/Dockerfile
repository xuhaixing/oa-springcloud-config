FROM docker.io/openjdk:11
VOLUME /tmp
ADD config-service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar","--spring.profiles.active=test"]