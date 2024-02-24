FROM eclipse-temurin:17-jdk-alpine
VOLUME /scraping
ARG JAR_FILE
COPY ${JAR_FILE} scraping.jar
ENTRYPOINT ["java","-jar","/scraping.jar"]