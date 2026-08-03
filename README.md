# Apache Storm (apache-storm)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
