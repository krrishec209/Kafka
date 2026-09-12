I couldn’t understand how 𝗞𝗮𝗳𝗸𝗮 is applied at Scale for system design until I started reading these technical blogs on 𝗞𝗮𝗳𝗸𝗮 implementation by big giants: 

• Dropbox's Kafka Throughput Limits: (https://lnkd.in/gqpwjHzv) 

• Shopify's Kafka on Kubernetes: (https://lnkd.in/gSdHqzb4) 

• Pinterest's Kafka at Scale: (https://lnkd.in/gb5skEtU) 

• Hulu's Million Metrics per Second: (https://lnkd.in/gRnBFEUv) 

• Criteo's Kafka Upgrade: (https://lnkd.in/gwGx8wvq) 

• Salesforce's Kafka-Inspired Architecture: (https://lnkd.in/gBH3bwGq) 

• Uber's Kafka Reprocessing: (https://lnkd.in/gti2xZuR) 

• Walmart's Cost Orchestration: (https://lnkd.in/gdtc5Az9) 

• Yelp's Kafka on Kubernetes: (https://lnkd.in/gkcfT-Vq) 

• NYT's Publishing with Kafka: (https://lnkd.in/gqcwF_zP) 

• Yelp's Billions of Messages: (https://lnkd.in/g7_fcfB7) 

Some more free resources on 𝗞𝗮𝗳𝗸𝗮: 
- https://lnkd.in/dP3wziT6
- https://lnkd.in/dhz-kJB5
- https://lnkd.in/drZ_hbq2
- https://lnkd.in/dSr77EcE
- https://lnkd.in/dDND2e6z

  https://www.linkedin.com/posts/anshul-chhabra-46ba9b113_i-couldnt-understand-how-%F0%9D%97%9E%F0%9D%97%AE%F0%9D%97%B3%F0%9D%97%B8%F0%9D%97%AE-is-applied-activity-7298574661359976452-4HaN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg

https://medium.com/agoda-engineering/how-agoda-manages-1-8-trillion-events-per-day-on-kafka-1d6c3f4a7ad1

***************


Kafka interview questions

𝗣𝗛𝗔𝗦𝗘 𝟭 - 𝗕𝗮𝘀𝗶𝗰𝘀

• What is Apache Kafka and what are its main use cases?
• Explain the key components of Kafka: Producer, Consumer, Broker, Topic, Partition.
• What is a Kafka topic and how does partitioning work in Kafka?
• Difference between Kafka and traditional message queues?
• What is a consumer group in Kafka, and how does it help in load balancing?

𝗣𝗛𝗔𝗦𝗘 𝟮 - 𝗜𝗻𝘁𝗲𝗿𝗺𝗲𝗱𝗶𝗮𝘁𝗲

• Explain how Kafka ensures message durability and fault tolerance.
• What is ISR (In-Sync Replicas) in Kafka?
• How does Kafka handle message ordering and delivery semantics (at-least-once, exactly-once, at-most-once)?
• What is the role of Kafka Zookeeper?
• Explain Kafka producer acknowledgments (acks=0, acks=1, acks=all).

𝗣𝗛𝗔𝗦𝗘 𝟯 - 𝗔𝗱𝘃𝗮𝗻𝗰𝗲𝗱

• Explain Kafka’s exactly-once semantics and how it is implemented.
• What is Kafka log compaction and when would you use it?
• Difference between Kafka Streams and Kafka Connect.
• How do you tune Kafka performance for high-throughput systems?
• Explain the end-to-end flow of data in a real-time streaming pipeline using Kafka integrated with other GCP services like Dataflow or BigQuery.

𝗜 𝗵𝗮𝘃𝗲 𝗽𝗿𝗲𝗽𝗮𝗿𝗲𝗱 𝗶𝗻 𝗗𝗲𝗽𝘁𝗵 𝗗𝗮𝘁𝗮 𝗘𝗻𝗴𝗶𝗻𝗲𝗲𝗿𝗶𝗻𝗴 𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄 𝗘𝘅𝗽𝗲𝗿𝗶𝗲𝗻𝗰𝗲𝘀 𝗳𝗼𝗿 𝟭𝟬𝟬+ 𝗖𝗼𝗺𝗽𝗮𝗻𝗶𝗲𝘀

𝗚𝗲𝘁 𝘁𝗵𝗲 𝗘𝘅𝗽𝗲𝗿𝗶𝗲𝗻𝗰𝗲𝘀 𝗛𝗲𝗿𝗲 - https://lnkd.in/giY6RZu2
𝗦𝘂𝗯𝘀𝗰𝗿𝗶𝗯𝗲 𝘁𝗼 𝗺𝘆 𝘆𝗼𝘂𝘁𝘂𝗯𝗲 𝗰𝗵𝗮𝗻𝗻𝗲𝗹 𝗵𝗲𝗿𝗲 - https://lnkd.in/dCyr4aph

https://www.linkedin.com/posts/shubhamwadekar_kafka-interview-questions-%F0%9D%97%A3%F0%9D%97%9B%F0%9D%97%94%F0%9D%97%A6%F0%9D%97%98-%F0%9D%9F%AD-activity-7314653149674229760-v2Le?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg

***************

🚀 Kafka vs RabbitMQ — Two Messaging Giants, Two Very Different Purposes
Choosing the right messaging system isn’t about popularity — it’s about understanding how your data flows.
🔵 Kafka → Think of it as a high-speed highway loop.
 It’s built for:
 • Continuous event streams
 • High throughput
 • Long-term data retention
 • Real-time processing
 • Publish–subscribe models
🟢 RabbitMQ → More like a structured mailroom.
 It excels at:
 • Reliable message delivery
 • Task & worker queues
 • Flexible routing
 • Point-to-point communication
🎯 Bottom line:
 Use Kafka when you need streaming at scale.
 Use RabbitMQ when you need guaranteed delivery and job-based messaging.
Making the right choice can drastically improve the performance and reliability of your distributed systems.

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/f86bce96-7e8b-4d55-8b7e-d03937a6d87b" />

********************************

Kafka is mandatory for any Backend / Java / Microservices interview. This one sheet covers 90% of what they ask.

Here are the 10 questions that decide if you get selected or rejected:

*1. Kafka Architecture*
Producer → Kafka Cluster [Broker 1,2,3] → Consumer Group. Zookeeper/KRaft manages metadata.

*2. acks=0, acks=1, acks=all?*
- acks=0: No ack, fastest but data loss possible
- acks=1: Leader ack only
- acks=all: All ISR ack. Safest but slowest

*3. How to prevent duplicate payment processing?*
My go-to answer in interviews:
- Enable idempotent producer `enable.idempotence=true`
- Store processed message IDs in DB (idempotency key)
- Use Kafka Transactions + Exactly-Once

*4. What if 6 partitions and 8 consumers in one group?*
Only 6 will be active. 2 will be idle. Max active consumers = number of partitions.

*5. How to maintain ordering for same Order ID?*
Use Order ID as message key. All events for same key go to same partition. Ordering is guaranteed WITHIN a partition only.

*6. What is Dead Letter Topic (DLT)?*
When message fails after all retries, send it to DLT for manual inspection. Never lose the message.

*7. At-Most-Once vs At-Least-Once vs Exactly-Once?*
- At-Most-Once: `acks=0` + auto commit → May lose, never duplicate
- At-Least-Once: `acks=all` + auto commit → Never lose, may duplicate
- Exactly-Once: Idempotent + Transactions + manual commit → Never lose, never duplicate

*8. Consumer Lag?*
Difference between latest offset and consumer's committed offset. Monitor via Kafka UI, Grafana, or `kafka-consumer-groups.sh`

*9. Kafka vs RabbitMQ?*
Kafka = Log-based, High Throughput, Streaming, Per Partition Ordering
RabbitMQ = Queue-based, Moderate Throughput, Task Queue, Per Queue Ordering

*10. Real Design: Order → Payment → Inventory*
Order Service → `order-topic` → Payment Service → `payment-topic` → Inventory Service. Each service consumes and produces events. Async, scalable, fault-tolerant.

*Bonus - How to create Producer in Spring Boot?*
Just configure `ProducerFactory<String, Order>` with Bootstrap servers and JsonSerializer. Consumer? Just `@KafkaListener(topics="order-topic")`

This cheat sheet has 50 Q&A. If you learn this, you can crack Kafka in any FAANG / Product interview.

I’ve saved this as my pre-interview revision note.


<img width="800" height="1209" alt="image" src="https://github.com/user-attachments/assets/a10f87dd-5f69-43b7-82e1-e8aaf04bff36" />


https://lnkd.in/p/gjV6-p8N

**************

I used to think Kafka is complex. It's not. It's just 3 concepts + Java code.

*1. WHAT IS KAFKA?*
A distributed event streaming platform. Not a queue. It's a log.

Think: Your microservices don't call each other directly. They publish events to Kafka. Whoever needs it, consumes it.

Order Service → `Order Placed Event` → Kafka → Payment Service, Inventory Service, Notification Service all consume independently.

*2. THE 5 CORE CONCEPTS YOU MUST KNOW*

- *Producer*: Sends messages
- *Topic*: A category/feed name (e.g., `order-topic`)
- *Partition*: Topic is split into partitions. This gives scalability + parallelism
- *Broker*: Kafka server that stores data
- *Consumer Group*: Group of consumers. Each partition is consumed by only ONE consumer in a group.

*Key Rule: Ordering is guaranteed only WITHIN a partition.* Want all events for same Order ID in order? Use Order ID as key.

*3. KAFKA WITH JAVA / SPRING BOOT - THE ACTUAL CODE*

*Producer Config:*
@Bean
public ProducerFactory<String, Order> producerFactory() {
    Map<String, Object> config = new HashMap<>();
    config.put(ProducerConfig.BOOTSTRAP_SERVERS_CONFIG, "localhost:9092");
    config.put(ProducerConfig.KEY_SERIALIZER_CLASS_CONFIG, StringSerializer.class);
    config.put(ProducerConfig.VALUE_SERIALIZER_CLASS_CONFIG, JsonSerializer.class);
    // For Exactly-Once
    config.put(ProducerConfig.ENABLE_IDEMPOTENCE_CONFIG, true);
    return new DefaultKafkaProducerFactory<>(config);
}

@Bean
public KafkaTemplate<String, Order> kafkaTemplate() {
    return new KafkaTemplate<>(producerFactory());
}

// Sending
kafkaTemplate.send("order-topic", order.getId(), order);
*Consumer Config:*
@KafkaListener(topics = "order-topic", groupId = "order-group")
public void listen(Order order, Acknowledgment ack) {
    // process payment
    paymentService.process(order);
    ack.acknowledge(); // Manual commit - More reliable
}
*4. THE INTERVIEW KILLER QUESTIONS*

*`acks=all` vs `acks=1` vs `acks=0`?*
- `0` = Fastest, may lose data
- `1` = Leader ack only
- `all` = All ISR replicas ack. Safest.

*How to handle duplicates?*
Idempotent Producer + Store message ID in DB as idempotency key.

*What if 6 partitions, 8 consumers?*
Only 6 consumers will be active. 2 will be idle. Max parallelism = partitions.

*How to scale consumers for high traffic?*
Increase partitions + Increase consumers in group. Or add new consumer groups.

*5. WHEN TO USE KAFKA?*
Don't use Kafka for everything.
Use REST API for sync request/response.
Use Kafka for async, high-throughput, streaming, event-driven systems.

*Real Flow I use in production:*
Order Service → publishes to `order-topic` → Payment Service consumes → publishes to `payment-topic` → Inventory Service consumes and updates stock.

Async, fault-tolerant, scalable.

https://lnkd.in/p/gefgBygu

