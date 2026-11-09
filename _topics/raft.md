---
layout: topic
slug: raft
name: Raft
kind: concept
description: Raft is a consensus algorithm for distributed systems designed to be understandable and provide the same guarantees as Paxos, used for distributed log replication and leader election in fault-tolerant systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/raft.png
tags:
- Consensus
- Distributed Systems
- Raft
- Algorithms
- Replication
area: database
repo: https://github.com/api-evangelist/raft
api_count: 0
apis: []
links:
- type: Documentation
  url: https://raft.github.io/
- type: Paper
  url: https://raft.github.io/raft.pdf
- type: SourceCode
  url: https://github.com/raft
provider_count: 2
providers:
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: apache-helix
  name: Apache Helix
  description: Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST A…
  api_count: 1
  score_band: thin
  score_composite: 37.1
  shared: 2
---
