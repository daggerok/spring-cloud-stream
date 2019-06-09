spring-cloud-stream [![build](https://travis-ci.org/daggerok/spring-cloud-stream.svg?branch=master)](https://travis-ci.org/daggerok/spring-cloud-stream)
====================

using rabbit

```fish
docker-compose up -d
gradle --parallel :producer:bootRun :consumer:bootRun
^C
docker-compose down
```

see other repo:

- [spring-cloud-function and spring-cloud-stream integration](https://github.com/daggerok/spring-cloud-function-stream-integration)
