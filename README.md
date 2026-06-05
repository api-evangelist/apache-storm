# Apache Storm (apache-storm)

Apache Storm is a free and open-source distributed real-time computation system that makes it easy to reliably process unbounded streams of data at scale. It provides a simple programming model (topologies with spouts and bolts), guaranteed message processing, horizontal scalability, and fault tolerance. Storm integrates with queuing and database technologies including Apache Kafka and Apache Cassandra and is governed by the Apache Software Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-storm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-storm/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Distributed Computing
- Event Processing
- Real-Time
- Stream Processing
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Storm REST API

The Storm UI REST API provides HTTP endpoints for monitoring and managing Storm clusters, topologies, and components. It exposes cluster summary, topology listing, topology detail, component statistics, supervisor info, nimbus info, and topology actions (activate, deactivate, rebalance, kill). The API serves the Storm UI dashboard and can be used programmatically.

- **Human URL:** [https://storm.apache.org/releases/current/STORM-UI-REST-API.html](https://storm.apache.org/releases/current/STORM-UI-REST-API.html)

#### Tags

- REST
- Monitoring
- Cluster Management
- Topologies

#### Properties

- [Documentation](https://storm.apache.org/releases/current/STORM-UI-REST-API.html)
- [OpenAPI](openapi/apache-storm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-storm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-storm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Storm Topology API

The Storm Topology API provides Java and other language bindings for building real-time processing topologies composed of spouts (data sources) and bolts (processing units). It supports various stream groupings, windowing operations, Trident micro-batch processing, and DRPC (Distributed Remote Procedure Calls) for synchronous request/response patterns.

- **Human URL:** [https://storm.apache.org/documentation/Tutorial.html](https://storm.apache.org/documentation/Tutorial.html)

#### Tags

- Java
- Topology
- Streaming
- Processing

#### Properties

- [Documentation](https://storm.apache.org/documentation/Tutorial.html)
- [SDK](https://search.maven.org/search?q=org.apache.storm)
- [Postman Collection](collections/apache-storm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-storm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/storm)
- [Documentation](https://storm.apache.org/documentation/Home.html)
- [Portal](https://storm.apache.org/)
- [Getting Started](https://storm.apache.org/releases/current/Setting-up-development-environment.html)
- [Release Notes](https://github.com/apache/storm/releases)
- [Support](https://storm.apache.org/contribute/People.html)
- [Terms of Service](https://www.apache.org/licenses/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
