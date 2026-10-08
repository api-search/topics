---
layout: topic
slug: acid
name: ACID
kind: topic
description: ACID (Atomicity, Consistency, Isolation, Durability) is a set of properties that guarantee database transactions are processed reliably even in the face of errors, power failures, or system crashes. These four properties ensure that data remains accurate and consistent, making ACID compliance a fundamental requirement for relational databases, distributed systems, and financial APIs.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/acid.png
tags:
- ACID
- Database
- Transaction
- Atomicity
- Consistency
- Isolation
- Durability
- Distributed Systems
repo: https://github.com/api-evangelist/acid
api_count: 5
apis:
- name: PostgreSQL Transaction API
  description: PostgreSQL provides full ACID compliance through its transaction management system including BEGIN, COMMIT, ROLLBACK, SAVEPOINT, and isolation level controls (READ COMMITTED, REPEATABLE READ, SERIALIZABLE). PostgreSQL uses Multi-Version Co…
  url: https://www.postgresql.org/docs/current/transaction-iso.html
- name: CockroachDB Distributed SQL API
  description: CockroachDB is a distributed SQL database providing serializable ACID transactions across multiple nodes and regions. It uses the Raft consensus algorithm and supports the PostgreSQL wire protocol. CockroachDB offers REST and SQL APIs for…
  url: https://www.cockroachlabs.com/docs/stable/
- name: Google Spanner API
  description: Google Spanner is a globally distributed, externally consistent database providing ACID transactions at global scale using TrueTime clock synchronization (GPS receivers and atomic clocks). The Cloud Spanner API offers both read-write trans…
  url: https://cloud.google.com/spanner/docs/transactions
- name: Amazon Aurora Transactions API
  description: Amazon Aurora provides ACID-compliant transactions for both MySQL-compatible and PostgreSQL-compatible editions. Aurora's distributed storage layer provides durability across 3 availability zones with 6-way replication. The Aurora Data API…
  url: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.html
- name: Atomikos Transaction API
  description: Atomikos provides ACID transaction management middleware for distributed microservices, supporting XA transactions across REST services using the Try-Confirm/Cancel (TCC) pattern. It enables ACID guarantees spanning multiple databases and…
  url: https://www.atomikos.com/
links:
- type: SecurityPolicy
  url: https://github.com/postgres/postgres/blob/master/.github/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/postgres/postgres/blob/master/.github/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/postgres/postgres/blob/master/.github/CONTRIBUTING.md
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/acid/blob/main/security/acid-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/acid/blob/main/security/acid-domain-security.yml
- type: Website
  url: https://en.wikipedia.org/wiki/ACID
- type: GitHubRepository
  url: https://github.com/cockroachdb/cockroach
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/json-ld/acid-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/vocabulary/acid-vocabulary.yaml
provider_count: 6
providers:
- slug: tikv
  name: TiKV
  description: TiKV is a CNCF-graduated distributed transactional key-value database built in Rust with Raft consensus. Originally created to complement TiDB, it provides horizontal scalability, strong consistency, and high availability with ACID transac…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: vitess
  name: Vitess
  description: Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable f…
  api_count: 4
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: redplanetlabs
  name: Redplanetlabs
  description: Red Planet Labs builds Rama, a unified backend platform for the JVM (Java/Clojure) that consolidates databases, queues, workers, and infrastructure into a single programming model — aiming to reduce backend complexity by up to 100x while p…
  api_count: 1
  score_band: emerging
  score_composite: 25.6
  shared: 2
- slug: riak
  name: Riak KV
  description: 'Riak KV is a distributed NoSQL key-value database originally developed by Basho Technologies, designed for high availability, fault tolerance, and horizontal scalability across commodity hardware. Riak exposes two client-facing APIs: a RES…'
  api_count: 1
  score_band: emerging
  score_composite: 24.4
  shared: 2
- slug: tigerbeetle
  name: TigerBeetle
  description: TigerBeetle is an open-source (Apache 2.0) distributed financial accounting and transactions database, purpose-built for high-throughput, mission-critical double-entry bookkeeping and online transaction processing (OLTP). It is NOT an HTTP…
  api_count: 4
  score_band: emerging
  score_composite: 14.3
  shared: 2
- slug: fauna
  name: Fauna
  description: Fauna, Inc. built a distributed document-relational database delivered as a cloud API, combining the relational query power of SQL with the flexibility of documents, global serverless distribution and strictly serializable ACID transaction…
  api_count: 1
  score_band: minimal
  score_composite: 0
  shared: 2
---
