+++
title = "On Kafka"
outputs = ["Reveal"]
+++

# On Kafka

---

<https://on-kafka.netlify.app>

---

## What Is Kafka?

> Apache Kafka is an open-source distributed **event streaming** platform

---

## What Is Event Streaming?

- Capturing data from event sources
- Storing these event streams durably
- Reacting to the event streams

---

## So What Is Kafka?

- Publish/subscribe messaging system
- Distributed commit log
- Data is stored durably, in order, and can be read deterministically

---

## What is Publish/Subscribe Messaging?

- Publish/subscribe messaging is a [pattern](https://www.enterpriseintegrationpatterns.com/patterns/messaging/PublishSubscribeChannel.html)
- **Publishers** (producers) send messages to a topic
- **Subscribers** (consumers) read messages from a topic
- A **topic** is like a database table or folder in a filesystem and decouples publishers and subscribers
- Pub/sub systems often have a **broker**, a central point where messages are published

---

## Kafka Cluster

<img src="images/kafka_cluster.png" height="450">

<sup><sup>[image credits](https://learning.oreilly.com/library/view/kafka-the-definitive/9781492043072/assets/ktdg_0107.png)</sup></sup>

---

## Producers

<img src="images/topic_producers.png" height="450">

<sup><sup>[image credits](https://learning.oreilly.com/library/view/kafka-the-definitive/9781492043072/assets/ktdg_0105.png)</sup></sup>

---

## Consumers

<img src="images/topic_consumers.png" height="450">

<sup><sup>[image credits](https://learning.oreilly.com/library/view/kafka-the-definitive/9781492043072/assets/ktdg_0106.png)</sup></sup>

---

### Why Kafka?

- Multiple producers
- Multiple consumers
- Disk-based retention
- Scalable
- High performance

---

### Use Cases

- Stream processing (data science, Hadoop)
- Messaging
- Activity tracking (websites, LinkedIn)
- Metrics and logging
- Commit log

---

### Challenges

- Distributed systems are complex ([first law](https://martinfowler.com/bliki/FirstLaw.html))
- Kafka is difficult to operate
- Many parameters: replication factor, ISR, retention, ...
- Logic within clients (consumers and producers)

---

## References

- [Kafka: The Definitive Guide](https://learning.oreilly.com/library/view/kafka-the-definitive/9781492043072/)
- [kafka.apache.org](https://kafka.apache.org)
- [Confluent Platform](https://docs.confluent.io/platform/current/overview.html)

---

### whoami

- Johann Gyger
- Passionate Software Engineer
- Twitter [@johanngyger](https://twitter.com/johanngyger)
- Consultant at [Levingo](https://levingo.ch/)
- Trainer at [acend](https://acend.ch/)
- Organizer of [Cloud Native Bern Meetup](https://www.meetup.com/cloudnativebern)
- Organizer of [Swiss Cloud Native Day](https://cloudnativeday.ch)
- [CNCF Ambassador](https://www.cncf.io/people/ambassadors/)

---

<https://github.com/johanngyger/on-kafka>