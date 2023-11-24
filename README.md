# Opora API

Repository to host static swagger ui API documentation for Opora group project

https://tarasshablii.github.io/opora-api/

# Back-end

Back-end API implementation can be started with the help of the attached docker-compose.yml

Start:
```shell
docker compose up -d
```
Back-end will be accessible at `localhost:8080`

Stop:
```shell
docker compose down
```

Created data will persist between runs in docker volumes. Remove docker volumes to wipe all data:
```shell
docker compose down -v
```