# Java App

Minimal web service built with Spring Boot and Maven. It listens on port `8080` by default and exposes `GET /health`.

## Prerequisites

- Java 17 or newer
- Maven 3.9 or newer

## Install and run

```sh
mvn spring-boot:run
```

Set `PORT` to use a different port:

```sh
PORT=3000 mvn spring-boot:run
```

Verify the service:

```sh
curl http://localhost:8080/health
```

Create an executable JAR with `mvn package`, then run it with:

```sh
java -jar target/java-app-0.1.0.jar
```