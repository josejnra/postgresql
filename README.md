# PostgreSQL

## How to Run
```shell
docker-compose up -d
```

Then if needed, in order to grant permissions to volumes:
```shell
sudo chmod 777 pgadmin omnidb_server
```

For adding user to omnidb:
```shell
docker exec -it omnidb python omnidb-server.py --createsuperuser=user pass
```
