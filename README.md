# Opora API

Repository to host static swagger ui API documentation for Opora group project

https://tarasshablii.github.io/opora-api/

# Back-end

Back-end API implementation can be started with the help of the attached docker-compose.yml

### Start

```shell
docker compose up -d
```

### Accessing the Application

* The application will be accessible on http://localhost:8080.
* Swagger UI for API documentation can be accessed at http://localhost:8080/swagger-ui/index.html.

### Stop

```shell
docker compose down
```

Created data will persist between runs in docker volumes. Remove docker volumes to wipe all data:

```shell
docker compose down -v
```