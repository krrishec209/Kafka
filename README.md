# Kafka
Kafka Resources


Kafka is Complicated,

until you go through these resources,

𝗙𝗿𝗲𝗲 𝗞𝗮𝗳𝗸𝗮 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲𝘀: 

1. Apache Kafka crash course with Spring Boot 3.0.x by Java Techie
 - https://lnkd.in/dP3wziT6
2. Apache Kafka with Spring Boot crash course by Daily Code Buffer
 - https://lnkd.in/dhz-kJB5
3. All about Kafka by Learning Tutorial
 - https://lnkd.in/drZ_hbq2
4. Kafka Tutorial by Intellipaat
 - https://lnkd.in/dSr77EcE
5. Kafka crash course by Hussein Nasser 
 - https://lnkd.in/dDND2e6z

𝗛𝗼𝘄 𝗞𝗮𝗳𝗸𝗮 𝗶𝗺𝗽𝗹𝗲𝗺𝗲𝗻𝘁𝗲𝗱 𝗮𝘁 𝗧𝗲𝗰𝗵 𝗚𝗶𝗮𝗻𝘁𝘀:

1. LinkedIn's Kafka Journey 
 - https://lnkd.in/d_QijMDk
2. Pinterest's Kafka at Scale
 - https://lnkd.in/dvV-8hun
3. Why Trello Chose Kafka
 - https://lnkd.in/gJhvX-dg
4. Salesforce's Kafka-Inspired Architecture
 - https://lnkd.in/gBH3bwGq
5. NYT's Publishing with Kafka
 - https://lnkd.in/gqcwF_zP
6. Yelp's Billions of Messages
 - https://lnkd.in/g7_fcfB7
7. Criteo's Kafka Upgrade 
 - https://lnkd.in/gwGx8wvq
8. Shopify's Kafka on Kubernetes
 - https://lnkd.in/gSdHqzb4
9. Yelp's Zero-Downtime Zookeeper Migration
 - https://lnkd.in/gHdphiQY
10. Uber's Kafka Reprocessing
 - https://lnkd.in/gti2xZuR
 - https://lnkd.in/gDF2S-vX
11. Dropbox's Kafka Throughput Limits
 - https://lnkd.in/gqpwjHzv
12. Walmart's Cost Orchestration
 - https://lnkd.in/gdtc5Az9
13. PayPal's Kafka Scaling
 - https://lnkd.in/gSxAVa89

𝗞𝗮𝗳𝗸𝗮 𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄 𝗤𝘂𝗲𝘀𝘁𝗶𝗼𝗻𝘀:

Basic Level:
1. What is Apache Kafka, and what are its core components?
2. Explain the difference between a topic, partition, and segment.
3. How does Kafka ensure message ordering?
4. What is a consumer group in Kafka?

Intermediate Level:
5. How does Kafka achieve fault tolerance? 
6. Explain Kafka's partitioning strategy and how it impacts performance.
7. Describe Kafka's consumer offset management.

Advanced Level:
8. Explain the concept of exactly-once semantics (EOS) in Kafka.
9. How would you monitor and optimize Kafka performance in a production environment? 
10. How would you design a Kafka-based system to guarantee data consistency in the event of node failures?

Over the years, I've explored Kafka's powerful capabilities in various projects, and I know firsthand how crucial the right resources are when implementing it from scratch. 

I’ve gathered some excellent free resources and insightful case studies that showcase how tech giants are using Kafka at scale. Plus, I’m shared a few key interview questions that helped me prepare and excel.

https://www.linkedin.com/in/rahul1n/

https://www.linkedin.com/posts/rahul1n_kafka-is-complicated-until-you-go-through-activity-7289849070821560321-Ah_T?utm_source=share&utm_medium=member_desktop


*****
Apache Kafka is a must-know for data engineering system design interviews. Learn Kafka's essentials in under 5 minutes 👇 

1. Topics 

> Logical grouping of events. 

- Topics group events in Kafka. 
- Producers push data to topics; consumers read from them. 
- Topics are configurable with retention policies and replication factors. 
Tip: Configure topics to balance retention needs and fault tolerance. 

2. Producers & Consumers 

> Producers send messages to topics; consumers read from them. 

- Producers write data; consumers process it. 
- Consumer groups coordinate multiple consumers to scale processing. 
- Topics are typically secured with ACLs/authentication. 
Example: Producers write clickstream data; consumer groups process it for real-time analytics. 

3. Partitions 

> A topic is split into partitions for scalability. 

- Kafka uses keys (hash-based) or round-robin to assign messages to partitions. 
- Custom partitioners can control event placement. 
Tip: More partitions = better scalability. Use keys to ensure strict ordering within a partition. 

4. Event Order 

> Kafka guarantees order within partitions, not across them.

- Use a key to send related events to the same partition. 
Example: Refund system ensures all events for the same order are processed in order. 

5. Log Compaction 

> Keep the latest event for each key. 

- Retains only the latest value for each key while removing older ones. 
- Compaction is done at the segment level. 
Use Cases: State tracking like user profiles or inventory levels. 

6. Acknowledgements 

> Ensure reliability with acknowledgements. 

- Producers: 
 - `acks=0`: No ack (fast, unreliable). 
 - `acks=1`: Leader ack (balanced). 
 - `acks=all`: Full ack (highest reliability). 
- Consumers: 
 - Auto-Commit: Offsets are committed automatically. 
 - Manual Commit: Commit offsets after successful processing. 
Tip: Use `acks=all` + manual commits for "at-least-once" guarantees. 

7. Brokers 

> Kafka servers that store data and serve clients. 

- Brokers store topic partitions. 
- Each partition has a leader broker (handles writes) and followers (replicas for fault tolerance). 
Tip: Monitor broker performance to avoid uneven load. 

8. Connectors 

> Use Kafka Connect to integrate with external systems. 

- Source Connectors: Pull data into Kafka (e.g., from MySQL). 
- Sink Connectors: Push Kafka data to external systems (e.g., Snowflake). 
- Single Message Transforms (SMTs): Modify data during ingestion or ejection. 
Use Cases: ETL pipelines, real-time replication, cloud integration. 

9. Data Retention Period 

> Determines how long messages are stored. 

- Time-Based Retention: Keep data for a duration (e.g., 7 days). 
- Size-Based Retention: Retain data until a partition reaches a size limit. 
- Log Compaction: Keep only the latest value for each key. 

What else should we cover? Let me know in the comments! 


https://www.linkedin.com/in/josephmachado1991/

https://www.linkedin.com/posts/josephmachado1991_data-kafka-dataengineering-activity-7292899808422342659-Y47k?utm_source=share&utm_medium=member_desktop


