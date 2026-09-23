---
layout: topic
slug: sketches
name: Sketches
kind: topic
description: Sketches are probabilistic data structures used in computing and data engineering to approximate answers to queries over large data streams with controlled error bounds and dramatically reduced memory requirements. Common sketches include Count-Min Sketch (frequency estimation), HyperLogLog (cardinality estimation), Bloom Filter (membership testing), and T-Digest (quantile estimation). APIs in this domain include sketch-native databases like Apache DataSketches, Redis probabilistic data structures, and cloud analytics services that implement sketch algorithms for real-time analytics, approximate query processing, and streaming analytics.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/sketches.png
tags:
- Data Structures
- Probabilistic Algorithms
- Streaming Analytics
- Approximate Query Processing
- Big Data
- Real-Time Analytics
repo: https://github.com/api-evangelist/sketches
api_count: 3
apis:
- name: Apache DataSketches API
  description: Apache DataSketches is the open-source library providing production-quality implementations of sketch algorithms including Theta Sketches (set operations), Quantiles Sketches (percentile estimation), HLL (HyperLogLog for cardinality), CPC,…
  url: https://datasketches.apache.org
- name: Redis Probabilistic Data Structures API
  description: Redis provides native probabilistic data structure commands through the Redis Stack (RedisBloom module), offering server-side implementations of Bloom Filter, Cuckoo Filter, Count-Min Sketch, Top-K, and HyperLogLog. These are accessible vi…
  url: https://redis.io/docs/data-types/probabilistic/
- name: Amazon Redshift Approximate Query API
  description: Amazon Redshift supports approximate query processing using HyperLogLog sketch functions (HLL_CREATE_SKETCH, HLL_COMBINE, HLL_CARDINALITY) for fast cardinality estimation on large datasets. These native SQL functions enable analytics teams…
  url: https://docs.aws.amazon.com/redshift/latest/dg/r_HLL_function.html
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/sketches/blob/main/security/sketches-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/sketches/blob/main/security/sketches-domain-security.yml
- type: Website
  url: https://datasketches.apache.org
- type: JSONLD
  url: https://github.com/api-evangelist/sketches/blob/main/json-ld/sketches-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/sketches/blob/main/vocabulary/sketches-vocabulary.yml
provider_count: 4
providers:
- slug: amazon-managed-apache-flink
  name: Amazon Managed Service for Apache Flink
  description: Amazon Managed Service for Apache Flink is the easiest way to transform and analyze streaming data in real time with Apache Flink. It enables you to build sophisticated streaming analytics applications using Apache Flink with fully managed…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 2
- slug: altinity
  name: Altinity
  description: Altinity is the enterprise provider for open-source ClickHouse, the real-time analytical database. It builds and operates Altinity.Cloud, a fully managed ClickHouse service available on AWS, GCP, Azure and Hetzner, plus a bring-your-own-cl…
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: apache-flink
  name: Apache Flink
  description: Apache Flink is a framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It provides a REST API for job management, cluster operations, metrics collection, and checkpoint management f…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 2
- slug: flink
  name: Apache Flink
  description: Apache Flink is an open-source framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It is designed to run in all common cluster environments and to perform computations at in-memory…
  api_count: 1
  score_band: emerging
  score_composite: 24.6
  shared: 2
---
