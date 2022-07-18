# spring-boot-kafka
This is a Spring Boot using apache kafka [kafka with java](https://developer.confluent.io/get-started/java/#prerequisites).

## Run it in the docker
```
docker-compose up -d
docker exec -t ecommerce_kafka_1 bash
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=ECOMMERCE_NEW_ORDER
```

## Compile and package

Being Maven centric, you can compile and package it without tests using:
```
mvn clean install -Dmaven.test.skip=true
```
Once you have your jar file, you can run it.

## Run it

To run it you can go click on intellij play as the image below:<br />

![](imgs/play_intellij.png)
