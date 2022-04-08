# Postgres + Pgadmin in Docker

1. Run containers
```sh
docker-compose up
```

2. Go to [pgadmin](http://localhost:5050)

```yaml
email: admin@admin.com
password: root
```

3. Create postgres server
```yaml
host: pg_container
port: 5432
user: root
password: root
```

4. Stop containers
```sh
docker-compose down
```