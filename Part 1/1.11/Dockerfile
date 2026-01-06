# Docker image
FROM amazoncorretto:latest

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

# Build project
RUN ./mvnw package

# Run
CMD ["java -jar ./target/docker-example-1.1.3.jar"]