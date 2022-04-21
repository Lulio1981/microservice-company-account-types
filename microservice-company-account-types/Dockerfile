FROM openjdk:11
EXPOSE 8008
ARG JAR_FILE=target/microservice-company-account-types 0.0.1-SNAPSHOT
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]