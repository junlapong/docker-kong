## Docker for Kong API Gateway

[Kong](https://konghq.com/kong/) and [Konga](https://pantsel.github.io/konga/)

![](https://raw.githubusercontent.com/pantsel/konga/master/screenshots/bc3.png)

## Docker Compose
```
docker-compose up -d
docker-compose logs -f
docker-compose down
```

### Docker Images
```
$ docker images
REPOSITORY          TAG                  IMAGE ID            CREATED             SIZE
postgres            9.5                  ce795f8066a6        2 weeks ago         227MB
kong                0.14                 f6a560387c57        2 months ago        92.3MB
pantsel/konga       0.13.0               9d7e3ce2b99e        7 months ago        371MB
```

## Open URL

### Kong API Gateway
- http://localhost:8000
<!-- - https://localhost:8443 -->

### Kong Admin API
- http://localhost:8001
<!-- - https://localhost:8444 -->

### Konga Dashboard
- http://localhost:1337

## References
 - [Kong in Docker Compose](https://github.com/Kong/docker-kong/tree/master/compose) 
 - [pantsel/docker-compose.yml](https://gist.github.com/pantsel/73d949774bd8e917bfd3d9745d71febf) and [mikkelkrogsholm/docker-compose.yml](https://gist.github.com/mikkelkrogsholm/d1188f1b416a891f56c54bb9a2016a55) *** OK ***
 - [Managing microservices and APIs with Kong and Konga](https://medium.com/@tselentispanagis/managing-microservices-and-apis-with-kong-and-konga-7d14568bb59d)
 - [ชีวิตดีเพราะมี Kong ช่วยทำ API Gateway](http://bit.ly/30HpYwM)
 - [ข้อดีและข้อเสียของ API Gateway](http://www.somkiat.cc/api-gateway-with-microservice/)