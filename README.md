# big-data-kafka-commands

### Command to start Zookeeper
'.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties'

### Command to start Kafka
'.\bin\windows\kafka-server-start.bat .\config\server.properties'

### Command to Execute Commands and Create Topic
'.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --create --topic DylanOpoka-messages
.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --list'

### Command to run Kafka Producer
'.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic DylanOpoka-messages'

### Command to run Kafka Consumer and Show Messages
'.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic DylanOpoka-messages --from-beginning

