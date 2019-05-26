## Docker for Kong API Gateway

[Kong](https://konghq.com/kong/) and [Konga](https://pantsel.github.io/konga/)

![](https://raw.githubusercontent.com/pantsel/konga/master/screenshots/bc3.png)

## Docker Compose
```
docker-compose up -d
docker-compose logs -f
docker-compose down
```
### Notes

```
$ docker images
REPOSITORY          TAG                  IMAGE ID            CREATED             SIZE
postgres            9.5                  ce795f8066a6        2 weeks ago         227MB
kong                latest               20ba91a7b0e5        4 weeks ago         98.5MB
pantsel/konga       next                 83d0f4e749be        7 weeks ago         389MB
```

## Open

### Service
- http://localhost:8000
<!-- - https://localhost:8443 -->

### Admin
- http://localhost:8001
<!-- - https://localhost:8444 -->

## References
 - [Kong in Docker Compose](https://github.com/Kong/docker-kong/tree/master/compose) 
 - [pantsel/docker-compose.yml](https://gist.github.com/pantsel/73d949774bd8e917bfd3d9745d71febf)

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue][github-new-issue].
