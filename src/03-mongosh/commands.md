## con este comando no conectamos a la terminal de mongo que esta en el proyecto mongodb de docker

## conect to conteiner

```sh
docker-compose exec mongodb bash
```

## conect with mongosh

```sh
mongosh "url"
```

```sh
show dbs
show collections
```

```sh
use('platzi_store')
db.products.find()
```