# Run docker compose
 ```
 docker-compose up -d
 ```
# Run docker file
```
docker run --name postgres-container -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=testWad -p 61111:5432 -d postgres:16

```