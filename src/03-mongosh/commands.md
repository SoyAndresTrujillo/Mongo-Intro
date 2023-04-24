## Connect to container
```sh
docker-compose exec mongodb bash
```

## Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://soyandrestrujillo:R2TmAhMvu7tNOMVu@mongodb-intro.q4jjedx.mongodb.net/?retryWrites=true&w=majority"
```

```sh
show dbs
show collections
```

```sh
db.products.find()
```