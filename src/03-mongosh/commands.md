## Connect to container

```sh
docker compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://user:password@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://user:password@mongodb777.abcdsoa.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("personal_store")
db.products.find()
```
