# Node Yarn Container

## Synopsis

Node Yarn Container is designed for speed, security, and flexibility.
```
Node Version: 16.18.0
Yarn Version: 3.2.4
```

## Running Locally

### Requirements
- Docker

### Building Container Image
```
docker build -t node_yarn:latest . -f ContainerFile
```

### Running Node Yarn Container Image
```
docker run --rm -it --name node_yarn \
 -p 3000:3000 \
 -v $PWD:/sync/ \
 brpedromaia/node_yarn:v2 bash
```
