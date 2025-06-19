# Kafka Java Producer Consumer Demo

A simple Java project demonstrating how to create a Kafka Producer using the official Kafka Client library.

## Features

✅ Kafka Producer in Java  
✅ Sending messages to Kafka topic  
✅ Basic Kafka configuration  
✅ Works with local Kafka broker (running via WSL2 or Docker)  
✅ Compatible with tools like Conduktor to view messages

## Tech Stack

- Java 17 (tested with Corretto 17.0.8)  
- Apache Kafka 3.1.0  
- Kafka Java Client Library  
- IntelliJ IDEA  
- Gradle

## Getting Started

### 1️⃣ Start Kafka Broker

Example (if running Kafka locally in WSL2):

```bash
~/kafka_2.13-3.1.0/bin/kafka-server-start.sh ~/kafka_2.13-3.1.0/config/server.properties
