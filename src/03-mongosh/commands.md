## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connetc with mongosh

```sh
mongosh "" 
```

```sh
show dbs
show collections 
```

```sh
use("david_store");
db.products.find(); 
```