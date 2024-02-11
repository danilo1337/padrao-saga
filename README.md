

## Mongo

Consultar dados no Mongo
``` sh
docker exec -it order-db mongosh "mongodb://admin:123456@localhost:27017"
use admin
show collections
db.event.find()
```
