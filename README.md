# Kafka Demo

A small .NET experiment for working with Apache Kafka through a producer/consumer setup.

The repository keeps the moving parts explicit instead of hiding the messaging flow behind a large application.

## Structure

```text
KafkaDemo/
├── Producer/
│   └── ProducerKafka.Console
├── Consumer/
│   └── ConsumerKafka.Console
└── Kafka.Setup.Docker/
    └── docker-compose.yml
```

### Producer

Publishes messages to Kafka from a console application.

### Consumer

Reads messages from Kafka from a separate console application.

### Kafka setup

Docker Compose configuration for running the local Kafka environment.

## What this project is for

This is a focused learning/engineering lab around:

- asynchronous messaging
- producer/consumer flow
- local Kafka infrastructure
- separating message publication from message processing

It is intentionally small. The goal is to make the message path easy to inspect.

## Status

**Engineering experiment.**

---

**Dat Tran / J.Andy**  
C# · .NET · Kafka · Distributed Systems