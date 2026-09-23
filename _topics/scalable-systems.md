---
layout: topic
slug: scalable-systems
name: Scalable Systems
kind: topic
description: A topic collection focused on APIs, tools, and platforms for designing and operating scalable distributed systems. Covers load balancing, auto-scaling, service discovery, distributed caching, message queues, and the cloud infrastructure APIs that enable systems to handle growth in data, traffic, and complexity. Relevant to site reliability engineers, infrastructure architects, and platform engineers responsible for operating high-scale production environments.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalable-systems.png
tags:
- Auto-Scaling
- Caching
- Cloud Infrastructure
- Distributed Systems
- High Availability
- Infrastructure
- Load Balancing
- Message Queue
- Platform Engineering
- Scalable Architecture
- Service Discovery
repo: https://github.com/api-evangelist/scalable-systems
api_count: 7
apis:
- name: AWS Auto Scaling API
  description: AWS Auto Scaling monitors applications and automatically adjusts capacity across multiple AWS resources including EC2, ECS, Lambda, DynamoDB, and Aurora. The API enables defining scaling policies, target tracking, and scheduled scaling for…
  url: https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html
- name: Redis REST API (Upstash)
  description: Redis is the dominant distributed in-memory cache and data structure store used to reduce latency and database load in scalable systems. Upstash provides a serverless Redis-compatible REST API for low-latency caching at scale.
  url: https://upstash.com/docs/redis/features/restapi
- name: Consul API
  description: HashiCorp Consul provides service discovery, health checking, key-value storage, and service mesh capabilities via a comprehensive REST API. Core component for service registry and dynamic configuration in scalable distributed systems.
  url: https://developer.hashicorp.com/consul/api-docs
- name: etcd API
  description: etcd is a strongly consistent, distributed key-value store used as the backing store for Kubernetes and many distributed systems. Its gRPC API provides atomic operations, watches, leases, and transactions for distributed coordination and c…
  url: https://etcd.io/docs/latest/learning/api/
- name: Celery Flower API
  description: Celery is a distributed task queue for Python applications. Flower is Celery's real-time monitoring tool that exposes an HTTP API for inspecting workers, tasks, queues, and scheduled jobs in production systems.
  url: https://flower.readthedocs.io/en/latest/api.html
- name: NGINX Plus API
  description: NGINX Plus provides an advanced REST API for runtime configuration and statistics of upstream server groups, virtual servers, and cache zones. Enables dynamic load balancer reconfiguration and real-time traffic monitoring without reloads.
  url: https://nginx.org/en/docs/http/ngx_http_api_module.html
- name: Scalable Systems ApplicationAutoScaling API
  description: The ApplicationAutoScaling API from Scalable Systems — 1 operation(s) for applicationautoscaling.
  url: https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/scalable-systems/blob/main/agentic-access/scalable-systems-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/scalable-systems/blob/main/security/scalable-systems-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/scalable-systems/blob/main/security/scalable-systems-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/scalable-systems/blob/main/authentication/scalable-systems-authentication.yml
- type: Guide
  url: https://www.nginx.com/resources/glossary/load-balancing/
- type: Guide
  url: https://aws.amazon.com/autoscaling/features/
- type: Guide
  url: https://redis.io/docs/manual/scaling/
- type: Guide
  url: https://www.consul.io/use-cases/service-discovery-and-health-checking
- type: Guide
  url: https://geeksforgeeks.org/distributed-systems/what-is-scalable-system-in-distributed-system/
- type: JSONSchema
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-schema/scalable-systems-load-balancer-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-structure/scalable-systems-load-balancer-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-ld/scalable-systems-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/scalable-systems/blob/main/vocabulary/scalable-systems-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-rabbitmq-queue-example.json
- type: Examples
  url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-consul-service-registration-example.json
provider_count: 26
providers:
- slug: haproxy
  name: HAProxy
  description: HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It exposes a Data Plane API for dynamic configuration management and a stats socket for r…
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 3
- slug: synadia-communications
  name: Synadia Communications
  description: Synadia Communications, Inc. is the creator and primary maintainer of NATS.io, the CNCF connectivity and messaging system, and sells the commercial platform built on it. Its products are Synadia Cloud (fully managed, globally distributed N…
  api_count: 2
  score_band: strong
  score_composite: 65.6
  shared: 2
- slug: amazon-elastic-load-balancing
  name: Amazon Elastic Load Balancing
  description: Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for…
  api_count: 1
  score_band: strong
  score_composite: 65.0
  shared: 2
- slug: microsoft-azure-cdn
  name: Microsoft Azure Cdn
  description: Azure Content Delivery Network (CDN) caches static web content at strategically placed edge locations to deliver it to users with maximum throughput and minimum latency. The product is operated through the Microsoft.Cdn Azure Resource Mana…
  api_count: 1
  score_band: strong
  score_composite: 62.2
  shared: 2
- slug: facets
  name: Facets
  description: Facets is an AI-native SDLC orchestrator and platform-engineering control plane that unifies infrastructure provisioning, CI/CD and configuration management into a single declarative blueprint model, so product teams get self-serve, drift-…
  api_count: 2
  score_band: strong
  score_composite: 61.0
  shared: 2
- slug: the-san-francisco-compute-company
  name: The San Francisco Compute Company
  description: The San Francisco Compute Company (SF Compute) runs large-scale, vetted GPU clusters and operates a compute marketplace where buyers reserve H100/H200 capacity by the hour and sellers resell unused compute back into the market with no long…
  api_count: 1
  score_band: strong
  score_composite: 57.7
  shared: 2
- slug: nuon
  name: Nuon
  description: Nuon is a Bring Your Own Cloud (BYOC) continuous-delivery platform for software vendors. It lets vendors package existing applications — Terraform, Pulumi, Helm charts, Kubernetes manifests, and container images — and deploy them into thei…
  api_count: 2
  score_band: strong
  score_composite: 55.5
  shared: 2
- slug: amazon-ec2-auto-scaling
  name: Amazon EC2 Auto Scaling
  description: Amazon EC2 Auto Scaling helps you maintain application availability and lets you automatically add or remove EC2 instances according to conditions you define. You can use fleet management features to maintain the health and availability of…
  api_count: 1
  score_band: strong
  score_composite: 55.2
  shared: 2
- slug: google-cloud-load-balancing
  name: Google Cloud Load Balancing
  description: Google Cloud Load Balancing provides high-performance, scalable load balancing for Google Cloud Platform services, distributing traffic across multiple instances, regions, and backends to ensure reliability and low latency.
  api_count: 1
  score_band: developing
  score_composite: 49.3
  shared: 2
- slug: microsoft-azure-load-balancer
  name: Azure Load Balancer
  description: Azure Load Balancer is a high-performance, low-latency layer-4 load balancing service for distributing inbound and outbound network traffic across virtual machines and other Azure resources. It supports public and internal load balancers,…
  api_count: 2
  score_band: developing
  score_composite: 47.9
  shared: 2
- slug: cast-ai
  name: CAST AI
  description: CAST AI is an Application Performance Automation (APA) platform for Kubernetes that automates cost optimization, autoscaling, workload rightsizing, GPU/LLM workload placement, spot instance selection, and security posture analysis. The pla…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: ironio
  name: Iron.io
  description: Iron.io provides hosted serverless infrastructure for background processing and asynchronous messaging. Its flagship products are IronMQ, a high-performance hosted message queue for passing messages and events between processes and systems…
  api_count: 2
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: kubernetes-services
  name: Kubernetes Services
  description: Kubernetes Services provide an abstract way to expose an application running on a set of Pods as a network service. They provide stable networking endpoints and load balancing across pod replicas in a Kubernetes cluster.
  api_count: 5
  score_band: developing
  score_composite: 43.9
  shared: 2
- slug: celery
  name: Celery
  description: Celery is an open-source distributed task queue for Python. It allows you to run tasks asynchronously in the background, enabling scalable distributed systems with support for multiple message brokers (RabbitMQ, Redis, Amazon SQS) and resu…
  api_count: 8
  score_band: thin
  score_composite: 39.0
  shared: 2
- slug: cloudquery
  name: CloudQuery
  description: CloudQuery is a cloud infrastructure data platform that gives platform engineering and cloud operations teams a queryable SQL data layer for visibility, governance, and automation. It syncs configuration data from AWS, GCP, Azure, and 70+…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: upbound
  name: Upbound
  description: Upbound is a universal cloud platform built on Crossplane, providing managed control planes and a marketplace for cloud infrastructure APIs. The Upbound API enables programmatic management of organizations, spaces, control planes, package…
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 2
- slug: flexera
  name: Spot by Flexera
  description: Spot by Flexera provides cloud infrastructure automation and optimization solutions. The platform includes Elastigroup for compute workload management across spot, reserved, and on-demand instances, Ocean for Kubernetes and container infra…
  api_count: 5
  score_band: thin
  score_composite: 35.8
  shared: 2
- slug: apache-geode
  name: Apache Geode
  description: Apache Geode is an in-memory data management platform that provides real-time, consistent access to data-intensive applications throughout widely distributed cloud architectures. It pools memory, CPU, network resources, and local disk stor…
  api_count: 1
  score_band: thin
  score_composite: 35.6
  shared: 2
- slug: a10-networks
  name: A10 Networks
  description: 'A10 Networks (NYSE: ATEN) is a San Jose, California–headquartered application delivery and cybersecurity company founded in 2004 by Lee Chen. A10 builds the ACOS (Application Centric Operating System) software platform that powers its Thun…'
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 2
- slug: apache-curator
  name: Apache Curator
  description: Apache Curator is a Java/JVM client library for Apache ZooKeeper, governed by the Apache Software Foundation, that provides a high-level API framework, fluent builders, and pre-built distributed coordination recipes including leader electi…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 2
- slug: moleculer
  name: Moleculer
  description: Moleculer is a fast, modern, and powerful microservices framework for Node.js. It provides built-in service discovery, load balancing, fault tolerance with circuit breaker, request retries, distributed event handling, and support for multi…
  api_count: 1
  score_band: thin
  score_composite: 32.6
  shared: 2
- slug: netflix-eureka
  name: Netflix Eureka
  description: Netflix Eureka is a RESTful service registry used for service discovery, load balancing, and failover of middle-tier servers in microservice and cloud-native architectures, originally built for the AWS cloud.
  api_count: 1
  score_band: emerging
  score_composite: 25.9
  shared: 2
- slug: alteon
  name: Alteon
  description: Alteon is Radware's application delivery controller (ADC) and advanced load balancer product line, providing Layer 4-7 load balancing, SSL/TLS offloading, application acceleration, global server load balancing, and integrated application s…
  api_count: 0
  score_band: emerging
  score_composite: 18.3
  shared: 2
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: emerging
  score_composite: 14.5
  shared: 2
- slug: avi-networks
  name: AVI Networks
  description: AVI Networks builds a software-defined application delivery platform - the Avi Vantage Platform / Avi Load Balancer - providing multi-cloud load balancing, web application firewall (WAF), GSLB, container ingress, and analytics driven by a…
  api_count: 0
  score_band: minimal
  score_composite: 8.7
  shared: 2
- slug: arrowpoint
  name: ArrowPoint
  description: 'ArrowPoint Communications, Inc. (NASDAQ: ARPT) was a networking company based in Acton, Massachusetts that built content switches — Layer 4-7 "web switches" that inspected HTTP content, cookies and URLs to route and load-balance traffic ac…'
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
