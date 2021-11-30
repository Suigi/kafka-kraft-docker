# kafka-kraft-docker

Fork of https://github.com/bashj79/kafka-kraft-docker that changes platform to arm64v8 (Apple Silicone).

A docker image for [Kafka](https://kafka.apache.org) without requiring Zookeeper.

For more information about the Kafka running in KRaft mode check out the [introductory blog post](https://www.confluent.io/blog/kafka-without-zookeeper-a-sneak-peek).


## Getting started

### Run with Docker

Build image

```
docker build . -t user/kafka-kraft
```

```
docker run -p 9092:9092 -d user/kafka-kraft
```

