FROM openjdk:17
COPY ./target/logs-2.7.1-SNAPSHOT.jar /usr/src/logs/
WORKDIR /usr/src/logs
EXPOSE 8580
CMD ["java", "-jar", "logs-2.7.1-SNAPSHOT.jar"]
