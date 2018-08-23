# Squid proxy

## Usage:
```
docker run --name proxy --restart=always -d -p 3128:3128 danielxlee/alpine-squid
```

## Manual Build docker images
```
docker build -t alpine-squid:latest .
```
