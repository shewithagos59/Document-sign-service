# Document-sign-service

Spring Boot backend for document-sign (minimal starter).

## Requirements
- Java 17+
- Maven 3.8+

## Build & Run
Build the project:

```bash
mvn clean package
```

Run with the Maven plugin:

```bash
mvn spring-boot:run
```

Or run the packaged jar:

```bash
java -jar target/document-sign-service-0.0.1-SNAPSHOT.jar
```

## Test

```bash
mvn test
```

## Verify
Start the app and check health endpoint:

```bash
curl -sS http://localhost:8080/health
# expected: {"status":"UP"}
```
