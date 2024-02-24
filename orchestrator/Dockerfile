FROM eclipse-temurin:17-jdk-alpine
VOLUME /orchestrator
ARG JAR_FILE
COPY ${JAR_FILE} orchestrator.jar
ENTRYPOINT ["java","-jar","/orchestrator.jar"]