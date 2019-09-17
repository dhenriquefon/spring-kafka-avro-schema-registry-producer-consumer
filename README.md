# spring-kafka-avro-schema-registry-producer-consumer
exemplo simples de produzir e escrever mensagens no KAFKA , utilizando protocolo AVRO e SCHEMA REGISTRY da CONFLUENT

First, install confluent platform: 
https://docs.confluent.io/current/quickstart/ce-quickstart.html?_ga=2.164882175.1581225892.1568655608-766627929.1567455964#ce-quickstart

Comandos para CONFLUENT:
 -> confluent local stop
 -> confluent local start
 -> confluent local status 
 
 control-center is [UP]
 ksql-server is [UP]
 connect is [UP]
 kafka-rest is [UP]
 schema-registry is [UP]
 kafka is [UP]
 zookeeper is [UP]
 
 
COMMAND TO BUILD APPLICATION
-> ./mvnw clean package

COMMAND TO RUN APPLICATION
-> java -jar target/kafka-avro-0.0.1-SNAPSHOT.jar
