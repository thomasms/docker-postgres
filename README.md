# Postgres in Docker

```bash
# setup and run
docker-compose build
docker-compose up -d
```

```bash
# check logs
docker logs docker_db_1
```

```bash
# connect with psql
psql --host=localhost --username=postgres --port=5551
```
