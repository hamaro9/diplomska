FROM openjdk:17
COPY ./target/gateway-2.7.1-SNAPSHOT.jar /usr/src/gateway/
WORKDIR /usr/src/gateway
EXPOSE 8000
CMD ["java", "-jar", "gateway-2.7.1-SNAPSHOT.jar"]
