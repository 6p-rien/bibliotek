# Image finale, sans les sources, juste avec le fichier JAR qu'on récupère du builder au dessus
FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY --from=builder /app/target/*.jar quest-boot.jar

EXPOSE 8080

CMD [ "java", "-jar", "quest-boot.jar" ]
