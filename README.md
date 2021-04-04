# redis-geo

run redis

```
docker run --rm --name geo-redis -p 6379:6379 redis
```

connect to redis

```
docker run -it --rm redis redis-cli -h host.docker.internal
```

