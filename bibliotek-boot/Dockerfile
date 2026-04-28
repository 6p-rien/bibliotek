# Image finale, sans les sources, juste avec le fichier JAR qu'on récupère du builder au dessus
FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY ./target/*.jar bibliotek-boot.jar

EXPOSE 8080

CMD [ "java", "-jar", "bibliotek-boot.jar" ]
