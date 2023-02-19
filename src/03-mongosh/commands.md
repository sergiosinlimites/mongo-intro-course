## Connect to container

```sh
sudo docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "connection-uri"
```

## Show information

```sh
show dbs
show collections
```

```sh
use("store")
db.products.find()
```
