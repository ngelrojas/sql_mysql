#### run mysql
```shell
    docker-compose up -d
```

#### connecting to mysql
```shell
    docker exec -it my-mysql mysql -p
```

#### import sql file from your filesystem
docker exec -it my-mysql mysql -p secret database_name < path-to-file.sql