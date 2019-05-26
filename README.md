## Docker for Kong API Gateway

[Kong](https://konghq.com/kong/) and [Konga](https://pantsel.github.io/konga/)

![](https://raw.githubusercontent.com/pantsel/konga/master/screenshots/bc3.png)

## Docker Compose
```
docker-compose up -d
docker-compose logs -f
docker-compose down
```

## Notes

```
$ docker images
REPOSITORY          TAG                  IMAGE ID            CREATED             SIZE
postgres            9.6                  8d9572468d97        2 weeks ago         230MB
kong                latest               20ba91a7b0e5        4 weeks ago         98.5MB
pantsel/konga       next                 83d0f4e749be        7 weeks ago         389MB
```

## Reference
 - [Kong in Docker Compose](https://github.com/Kong/docker-kong/tree/master/compose) 
 - [pantsel/docker-compose.yml](https://gist.github.com/pantsel/73d949774bd8e917bfd3d9745d71febf)