FROM openjdk:8u191-jdk-alpine3.9

MAINTAINER Mike "test@test123456.com"

EXPOSE 7070

WORKDIR /usr/local/bin

COPY ./target/Djoko.crm.web-0.0.1-SNAPSHOT-shaded.jar webapp.jar

CMD ["java", "-jar", "webapp.jar"]