FROM openjdk:17
COPY ./target/multiplication-2.7.1-SNAPSHOT.jar /usr/src/multiplication/
WORKDIR /usr/src/multiplication
EXPOSE 8080
CMD ["java", "-jar", "multiplication-2.7.1-SNAPSHOT.jar"]
