FROM eclipse-temurin:17-jdk-alpine
VOLUME /reports
ARG JAR_FILE
COPY ${JAR_FILE} reports.jar
ENTRYPOINT ["java","-jar","/reports.jar"]