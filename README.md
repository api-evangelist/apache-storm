# Apache Storm (apache-storm)
Apache Storm is a free and open-source distributed real-time computation system that makes it easy to reliably process unbounded streams of data at scale. It provides a simple programming model with topologies, spouts, and bolts, guaranteed message processing, and fault tolerance.

**URL:** [https://storm.apache.org/](https://storm.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Computing, Event Processing, Real-Time, Stream Processing, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Storm REST API
HTTP endpoints for monitoring and managing Storm clusters, topologies, and components including cluster summary, topology listing, topology detail, component statistics, and topology actions.

**Human URL:** [https://storm.apache.org/releases/current/STORM-UI-REST-API.html](https://storm.apache.org/releases/current/STORM-UI-REST-API.html)

#### Tags:

 - REST, Monitoring, Cluster Management, Topologies

#### Properties

- [Documentation](https://storm.apache.org/releases/current/STORM-UI-REST-API.html)

### Apache Storm Topology API
Java and multi-language API for building real-time processing topologies with spouts and bolts, stream groupings, windowing, Trident micro-batch, and DRPC.

**Human URL:** [https://storm.apache.org/documentation/Tutorial.html](https://storm.apache.org/documentation/Tutorial.html)

#### Tags:

 - Java, Topology, Streaming, Processing

#### Properties

- [Documentation](https://storm.apache.org/documentation/Tutorial.html)
- [Maven Java SDK](https://search.maven.org/search?q=org.apache.storm)

## Common Properties

- [GitHubRepository](https://github.com/apache/storm)
- [Documentation](https://storm.apache.org/documentation/Home.html)
- [Portal](https://storm.apache.org/)
- [GettingStarted](https://storm.apache.org/releases/current/Setting-up-development-environment.html)
- [ReleaseNotes](https://github.com/apache/storm/releases)
- [Support](https://storm.apache.org/contribute/People.html)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Guaranteed Message Processing | At-least-once processing guarantees through ack/fail tracking mechanism. |
| Scalable Topologies | Horizontally scalable stream processing topologies with configurable parallelism. |
| Trident API | High-level micro-batch processing abstraction with stateful streaming and exactly-once semantics. |
| DRPC | Distributed Remote Procedure Calls for synchronous distributed computation. |
| Windowing Operations | Tumbling and sliding window processing over bounded time or count windows. |
| Multi-Language Support | Topology components written in Java, Python, Ruby, and other languages. |

## Use Cases

| Name | Description |
|------|-------------|
| Real-Time Analytics | Continuous computation over live event streams for operational dashboards. |
| ETL Processing | Real-time data transformation and enrichment pipelines. |
| Machine Learning Scoring | Online scoring of ML models against streaming feature data. |
| Fraud Detection | Low-latency fraud detection rules applied to transaction streams. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Kafka Spout for consuming messages from Kafka topics as Storm data sources. |
| Apache Cassandra | CassandraBolt for writing processed stream data to Cassandra. |
| Apache Hive | HiveBolt for streaming inserts into Apache Hive tables. |
| Redis | Redis integration for stateful lookups and caching in Storm bolts. |
| Elasticsearch | ElasticsearchBolt for indexing stream data into Elasticsearch. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
