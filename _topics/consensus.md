---
layout: topic
slug: consensus
name: Consensus
kind: topic
description: Consensus is the distributed systems problem of getting a set of unreliable processes to agree on a value or sequence of values. Consensus algorithms power state-machine replication for databases, key-value stores, configuration systems, and blockchains. The consensus topic spans classical crash-fault tolerant algorithms (Paxos, Raft, Multi-Paxos, Zab, Viewstamped Replication) and Byzantine fault tolerant algorithms (PBFT, Tendermint, HotStuff, Casper FFG/CBC), and the impossibility result FLP that bounds what is possible in fully asynchronous models.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/consensus.png
tags:
- Algorithms
- BFT
- Blockchain
- Consensus
- Crash Fault Tolerance
- Distributed Systems
- Replication
- State Machine
repo: https://github.com/api-evangelist/consensus
api_count: 5
apis:
- name: Paxos
  description: Paxos is the classical crash-fault-tolerant consensus algorithm introduced by Leslie Lamport in 1989. Paxos and its derivatives (Multi-Paxos, Cheap Paxos, Vertical Paxos, EPaxos, Flexible Paxos) are foundational to distributed systems theo…
  url: https://lamport.azurewebsites.net/pubs/paxos-simple.pdf
- name: Raft
  description: Raft is a consensus algorithm designed for understandability, published by Ongaro and Ousterhout in 2014. Raft separates leader election, log replication, and safety into distinct concepts and is implemented widely in etcd, Consul, Cockroa…
  url: https://raft.github.io/
- name: Practical Byzantine Fault Tolerance (PBFT)
  description: PBFT, by Castro and Liskov (1999), is a Byzantine fault-tolerant consensus protocol that tolerates up to f Byzantine failures with 3f+1 replicas. PBFT influenced subsequent BFT protocols including Tendermint and HotStuff.
  url: http://pmg.csail.mit.edu/papers/osdi99.pdf
- name: Tendermint / CometBFT
  description: Tendermint (now CometBFT) is a Byzantine fault-tolerant consensus engine that powers Cosmos SDK chains. CometBFT decouples consensus from application logic via the Application Blockchain Interface (ABCI), allowing custom blockchain applica…
  url: https://docs.cometbft.com/
- name: HotStuff
  description: HotStuff is a leader-based BFT consensus protocol with linear view change and three-chain commit, designed by Yin et al. HotStuff is the foundation for Diem/Libra BFT and inspired modern protocols like Aptos AptosBFT and Sui's Mysticeti.
  url: https://arxiv.org/abs/1803.05069
links:
- type: IssueTracker
  url: https://github.com/cometbft/cometbft/issues
- type: Releases
  url: https://github.com/cometbft/cometbft/releases
- type: SecurityPolicy
  url: https://github.com/cometbft/cometbft/blob/main/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/cometbft/cometbft/blob/main/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/cometbft/cometbft/blob/main/CONTRIBUTING.md
- type: License
  url: https://github.com/cometbft/cometbft/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/consensus/blob/main/security/consensus-domain-security.yml
- type: Reference
  url: https://en.wikipedia.org/wiki/Consensus_(computer_science)
- type: Reference
  url: https://en.wikipedia.org/wiki/Paxos_(computer_science)
- type: Reference
  url: https://en.wikipedia.org/wiki/Raft_(algorithm)
- type: Reference
  url: https://en.wikipedia.org/wiki/Byzantine_fault
- type: Reference
  url: https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf
- type: Resources
  url: https://raft.github.io/
provider_count: 7
providers:
- slug: raft
  name: Raft
  description: Raft is a consensus algorithm for distributed systems designed to be understandable and provide the same guarantees as Paxos, used for distributed log replication and leader election in fault-tolerant systems.
  api_count: 0
  score_band: minimal
  score_composite: 7.6
  shared: 4
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 51.2
  shared: 2
- slug: apache-helix
  name: Apache Helix
  description: Apache Helix is a generic cluster management framework for partitioned and replicated distributed resources. It automates partition management, replication, fault tolerance, and cluster expansion for distributed systems, providing a REST A…
  api_count: 1
  score_band: developing
  score_composite: 39.8
  shared: 2
- slug: sapien
  name: Sapien
  description: Sapien is the company behind Proof of Quality (PoQ), an open protocol and consensus/attestation system for verifiable quality signals on AI data and subjective expert outputs. A panel of independent, collateral-backed validators reviews ea…
  api_count: 1
  score_band: developing
  score_composite: 39.4
  shared: 2
- slug: tendermint
  name: Tendermint
  description: Tendermint is a core contributor to the Cosmos Network and the original developer of Tendermint Core, a best-in-class Byzantine Fault Tolerant (BFT) consensus engine for state-machine replication, alongside the Cosmos SDK blockchain applic…
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: espresso
  name: Espresso
  description: Espresso Systems builds the Espresso Network, a high-performance consensus and sequencing layer that gives rollups and institution-grade financial applications real-time settlement (~3 second finality) without sacrificing control, privacy,…
  api_count: 1
  score_band: thin
  score_composite: 35.5
  shared: 2
- slug: cypherium
  name: Cypherium
  description: Cypherium is a permissionless Layer-1 blockchain built to bridge centralized (CeFi) and decentralized (DeFi) finance and bring real-world assets on-chain at scale. It runs CypherBFT, a hybrid consensus that pairs GPU proof-of-work committe…
  api_count: 2
  score_band: emerging
  score_composite: 13.9
  shared: 2
---
