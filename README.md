# docker-rabbitmq

## Build
```
docker build -t rabbitmq .
```

## Docker Run
```
docker run --name=rabbitmq -d -p 5672:5672 -p 15672:15672 -v data:/data -t rabbitmq
```

## Docker Compose
```
docker-compose up -d
```
