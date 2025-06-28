# Kafka Java Producer/Consumer Demo

A minimal Java application demonstrating Kafka client APIs.

## Highlights
- Plain Java producer and consumer using `org.apache.kafka.clients`
- Configurable via `application.properties`
- Docker image included for local Kafka environment
- Clean Maven structure with runnable main methods

## How to Use
1. Clone repo
2. Start Kafka with Docker or local install
3. `mvn clean package`
4. Run:
   ```bash
   java -cp target/demo.jar com.example.ProducerApp
   java -cp target/demo.jar com.example.ConsumerApp

## 📸 Demo

Kafka Streams application in action:

### 🔁 Real-Time Stream Processing  
Displays how messages flow through your Kafka Streams topology.  
![Stream Processing](screenshots/kafka_streams.jpg)

Kafka Streams application in action:

### 🔁 Real-Time Stream Processing  
Displays how messages flow through your Kafka Streams topology.  
![Stream Processing](screenshots/kafka_streams.jpg)

### 🔍 Consumer Group Monitoring  
Tracks the active consumer group and current lag.  
![Consumer Group State](screenshots/kafka-template.jpg)

### 🔄 Offset Reset via UI  
Reset Kafka offsets to reprocess historical events.  
![Offset Reset](screenshots/kafka-template2.jpg)
