FROM openjdk:18

MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"

EXPOSE 8080

WORKDIR /usr/loca/bin

COPY ./target/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

ENV JAVA_OPTS="-Dspring.profiles.active=docker-demo"

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]