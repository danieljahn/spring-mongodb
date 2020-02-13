# Spring MongoDB Example
Based on getting started guide [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/#scratch).

# Run
## Run MongoDB in docker
```console
docker pull mongo:latest
docker run --name mongodb -d -p 27017:27017 mongo:latest
```

## Run the app
```console
./mvnw spring-boot:run
```