# nginx-proxy

##how to use

Create network:
```bash
docker network create nginx-proxy-network
```

Run container
```bash
docker-compose up
```

if something went wrong force recreate
```bash
docker-compose up --force-recreate
```