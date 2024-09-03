# Knowledge Graph Demo

## Running Neo4j on docker

```
cp .env.example .env
docker-compose up neo4j
```

open http://localhost:7474



kubectl exec deploy/neo4j-v5 --namespace=harmonizome-kg -- mkdir /data/dumps

kubectl get pods --namespace=harmonizome-kg  

kubectl cp -n harmonizome-kg data/neo4j/dumps/neo4j.dump neo4j-v5-78c7ddffd5-gnsx9:/data/dump

kubectl exec deploy/neo4j-v5 --namespace=harmonizome-kg -- neo4j-admin database load neo4j --from-path=/data/dumps --overwrite-destination=true