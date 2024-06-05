# Docker compose multiple database postgres
 
 This is an example repo of how to create a single postgres service with multiple database


## To run

```bash
docker compose up -d
```


## to check
```bash
docker exec -it <container_name> bash
```
```bash
psql -U postgres
\l
```
