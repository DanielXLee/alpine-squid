# Squid proxy

## Usage:
```
docker pull danielxlee/alpine-squid
docker run -d -p 3128:3128 --name squid danielxlee/alpine-squid
```

## Build docker images
```
docker build -t danielxlee/alpine-squid:latest .
docker push danielxlee/squid-d:latest
```
