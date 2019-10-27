
# 概要
laravelが動くdocker

# start docker
```
docker-compose uo -d
```

# go in Php Container
```
docker-compose exec php bash
```

# create laravel project
```
# after went in php container 
laravel new
```

# go in mysql container
```
docker exec -it db-host bash
``` 