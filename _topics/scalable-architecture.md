---
layout: topic
slug: scalable-architecture
name: Scalable Architecture
kind: topic
description: A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patterns that enable distributed systems to scale reliably.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalable-architecture.png
tags:
- Cloud Architecture
- Cloud-Native
- Distributed Systems
- High Availability
- Infrastructure
- Microservices
- Performance
- Resilience
- Scalability
- Service Mesh
repo: https://github.com/api-evangelist/scalable-architecture
api_count: 8
apis:
- name: Istio Service Mesh API
  description: Istio is the leading open-source service mesh providing traffic management, security (mTLS), and observability for microservices. The Istio API includes VirtualService, DestinationRule, Gateway, and ServiceEntry custom resources for contro…
- name: Linkerd API
  description: Linkerd is a lightweight, security-first service mesh for Kubernetes. Built on Rust-based micro-proxy (linkerd2-proxy), Linkerd provides automatic mTLS, observability with golden metrics (success rate, latency, throughput), and traffic man…
- name: Envoy Proxy Admin API
  description: Envoy is a high-performance, open-source edge and service proxy, and the underlying data plane for Istio, Linkerd, and most service meshes. The Envoy Admin API provides REST endpoints for configuration, statistics, health checks, cluster m…
- name: Apache Kafka REST Proxy API
  description: The Confluent REST Proxy provides a RESTful interface to an Apache Kafka cluster, making it easy to produce and consume messages, view the state of the cluster, and perform administrative actions without using the native Kafka protocol. Ce…
- name: Redis REST API (Redis Stack)
  description: Redis is an in-memory data structure store used as a cache, message broker, and streaming engine. Redis Stack provides REST API access via the RedisJSON and RediSearch modules. Used extensively in scalable architectures for caching, sessio…
- name: RabbitMQ Management HTTP API
  description: RabbitMQ is a widely-deployed open-source message broker implementing AMQP, MQTT, STOMP, and other messaging protocols. The RabbitMQ Management HTTP API provides REST endpoints for managing exchanges, queues, bindings, users, and virtual h…
- name: Kubernetes API
  description: The Kubernetes API is the foundation of the container orchestration ecosystem, providing REST endpoints for managing the full lifecycle of containerized workloads. Core to scalable architecture, Kubernetes manages Deployments, Services, In…
- name: Argo Workflows API
  description: Argo Workflows is a Kubernetes-native workflow engine for orchestrating parallel jobs. Used extensively in scalable data pipelines, CI/CD systems, and ML workflows. Provides a REST API for submitting, monitoring, and managing workflows and…
links:
- type: Plans
  url: https://github.com/api-evangelist/scalable-architecture/blob/main/plans/scalable-architecture-plans-pricing.yml
- type: RateLimits
  url: https://github.com/api-evangelist/scalable-architecture/blob/main/rate-limits/scalable-architecture-rate-limits.yml
- type: FinOps
  url: https://github.com/api-evangelist/scalable-architecture/blob/main/finops/scalable-architecture-finops.yml
- type: CNCF Landscape
  url: https://landscape.cncf.io/
- type: GitHubOrganization
  url: https://github.com/cncf
- type: Blog
  url: https://www.cncf.io/blog/
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-microservice-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-schema/scalable-architecture-event-schema.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/json-ld/scalable-architecture-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/main/vocabulary/scalable-architecture-vocabulary.yml
provider_count: 70
providers:
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 53.2
  shared: 3
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 3
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 35.0
  shared: 3
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 34.9
  shared: 3
- slug: alibaba-sentinel
  name: Alibaba Sentinel
  description: Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production at Alibaba for over 10 years, Sentinel provides fl…
  api_count: 1
  score_band: emerging
  score_composite: 23.4
  shared: 3
- slug: open-service-mesh
  name: Open Service Mesh
  description: Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh built on Envoy and the Service Mesh Interface (SMI) specification. OSM provides traffic shifting, mutual TLS, access control, observability, and automatic side…
  api_count: 1
  score_band: emerging
  score_composite: 21.5
  shared: 3
- slug: new-relic
  name: New Relic
  description: New Relic offers an AI‑powered observability platform that provides application performance monitoring, digital experience monitoring, infrastructure monitoring, log management, and security services. The platform helps enterprises gain re…
  api_count: 5
  score_band: exemplar
  score_composite: 76.5
  shared: 2
- slug: synadia-communications
  name: Synadia Communications
  description: Synadia Communications, Inc. is the creator and primary maintainer of NATS.io, the CNCF connectivity and messaging system, and sells the commercial platform built on it. Its products are Synadia Cloud (fully managed, globally distributed N…
  api_count: 2
  score_band: exemplar
  score_composite: 72.1
  shared: 2
- slug: amazon-elastic-load-balancing
  name: Amazon Elastic Load Balancing
  description: Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for…
  api_count: 1
  score_band: strong
  score_composite: 66.3
  shared: 2
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 4
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 3
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: solo-io
  name: Solo.io
  description: Solo.io is a cloud-native application-networking company founded in 2017 that builds enterprise and open-source API gateways, service mesh, and agentic-AI infrastructure. Its products include Kgateway Enterprise (formerly Gloo Gateway), an…
  api_count: 5
  score_band: strong
  score_composite: 60.4
  shared: 2
- slug: websphere
  name: IBM WebSphere
  description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
  api_count: 7
  score_band: strong
  score_composite: 59.9
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: gloo
  name: Gloo
  description: Gloo is Solo.io's family of open-source and enterprise API gateway, service mesh and developer portal products, built on Envoy Proxy and Istio and delivered as software the customer runs in their own Kubernetes clusters rather than as a ho…
  api_count: 4
  score_band: strong
  score_composite: 57.9
  shared: 2
- slug: aws-app-mesh
  name: AWS App Mesh
  description: AWS App Mesh is a service mesh based on the Envoy proxy that provides application-level networking to make it easy for services to communicate with each other across multiple types of compute infrastructure including Amazon ECS, EKS, EC2,…
  api_count: 1
  score_band: strong
  score_composite: 55.0
  shared: 2
- slug: amazon-vpc-lattice
  name: Amazon VPC Lattice
  description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that…
  api_count: 73
  score_band: developing
  score_composite: 52.3
  shared: 2
- slug: docker
  name: Docker
  description: Docker is a platform for developers and sysadmins to build, share, and run applications in containers, packaging code and dependencies together for consistent deployment across environments.
  api_count: 1
  score_band: developing
  score_composite: 52.0
  shared: 2
- slug: virtual-instruments
  name: Virtana (Virtual Instruments)
  description: Virtana (formerly Virtual Instruments) is an AI-powered hybrid infrastructure observability company whose platform monitors and optimizes performance, cost, and risk across on-premises, colocation, and cloud environments. The platform span…
  api_count: 3
  score_band: developing
  score_composite: 49.1
  shared: 2
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: amazon-resilience-hub
  name: Amazon Resilience Hub
  description: AWS Resilience Hub provides a central place to define, validate, and track the resilience of your AWS applications. It assesses your application against your Recovery Time Objective (RTO) and Recovery Point Objective (RPO) targets and prov…
  api_count: 7
  score_band: developing
  score_composite: 47.0
  shared: 2
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. O…
  api_count: 1
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: haproxy
  name: HAProxy
  description: HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It exposes a Data Plane API for dynamic configuration management and a stats socket for r…
  api_count: 1
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium proje…
  api_count: 2
  score_band: developing
  score_composite: 42.8
  shared: 2
- slug: envoy
  name: Envoy
  description: Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the d…
  api_count: 3
  score_band: developing
  score_composite: 42.6
  shared: 2
- slug: chaos-mesh
  name: Chaos Mesh
  description: Chaos Mesh is a CNCF graduated cloud-native chaos engineering platform that orchestrates chaos experiments on Kubernetes to test system resilience and reliability. It exposes Kubernetes Custom Resource Definitions (CRDs) for a wide range o…
  api_count: 2
  score_band: developing
  score_composite: 42.2
  shared: 2
- slug: radius
  name: Radius
  description: Application platform for cloud-native applications that enables developers to define, deploy, and manage applications across multiple clouds and on-premises environments using a unified model.
  api_count: 5
  score_band: developing
  score_composite: 41.7
  shared: 2
- slug: apache-dubbo
  name: Apache Dubbo
  description: Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols includ…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 2
- slug: wasmcloud
  name: wasmCloud
  description: wasmCloud is a CNCF incubating platform for building, managing, and scaling distributed applications using WebAssembly components. It provides a runtime that manages the lifecycle of WebAssembly actors and capability providers, enabling de…
  api_count: 5
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: envoy-gateway
  name: Envoy Gateway
  description: Envoy Gateway is a CNCF project that manages Envoy Proxy as a standalone or Kubernetes-based application gateway. It implements the Kubernetes Gateway API and extends it with its own API group, gateway.envoyproxy.io, whose eight Custom Res…
  api_count: 3
  score_band: developing
  score_composite: 40.9
  shared: 2
---
