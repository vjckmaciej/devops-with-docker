# Etap 1: Budowanie aplikacji
FROM openjdk:17-jdk-slim

EXPOSE 8080

# Ustaw katalog roboczy
WORKDIR /usr/src/app

# Skopiuj pliki Maven
COPY . .

# Zbuduj aplikację
RUN ./mvnw package

# Uruchom aplikację
ENTRYPOINT ["java", "-jar", "./target/demo-0.0.1-SNAPSHOT.jar"]
