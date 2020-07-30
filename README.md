# Hello Kafka

Very Simple minimal application to demonestrate a Producer that takes user entries from terminal and produces an event in Kafka running in localhost
and a consumer that displays the consumed messages in the terminal

## Quickly run Kafka
First run the Zookeeper
```
bin/zookeeper-server-start.sh config/zookeeper.properties
```
Then Run Kafka with the default poperties
```
bin/kafka-server-start.sh config/server.properties
```
