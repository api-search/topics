---
layout: topic
slug: scalability
name: Scalability
kind: topic
description: A subject-matter collection covering APIs, tools, frameworks, and data sources related to application scalability, infrastructure scaling, performance optimization, and elastic resource management. This topic spans cloud provider auto-scaling, event-driven autoscaling (KEDA), load balancing, database scaling, and observability for scale.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalability.png
tags:
- Auto-Scaling
- Cloud Computing
- DevOps
- Distributed Systems
- Elasticity
- High Availability
- Infrastructure
- Load Balancing
- Performance
- Scalability
repo: https://github.com/api-evangelist/scalability
api_count: 7
apis:
- name: KEDA (Kubernetes Event-Driven Autoscaling) API
  description: KEDA is a Kubernetes-based event-driven autoscaling component and CNCF graduate project. It provides fine-grained autoscaling (including to/from zero) for event-driven Kubernetes workloads by bridging over 70 built-in scalers to message br…
- name: AWS Auto Scaling API
  description: Amazon Web Services Auto Scaling monitors applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Supports EC2 Auto Scaling, Application Auto Scaling for ECS, DynamoDB, Lambd…
- name: Google Cloud Compute Engine Autoscaler API
  description: Google Cloud's Autoscaler API enables automatic scaling of managed instance groups based on CPU utilization, load balancing capacity, or Cloud Monitoring metrics. Integrates with Google Kubernetes Engine (GKE) for cluster autoscaling and n…
- name: Azure Autoscale REST API
  description: Microsoft Azure Autoscale provides a REST API for managing autoscale settings on Azure resources including Virtual Machine Scale Sets, App Service, and Azure Container Apps. Supports schedule-based and metric-based scaling rules with notif…
- name: CloudWatch Application Signals API
  description: Amazon CloudWatch Application Signals provides application performance monitoring (APM) to help detect and diagnose performance issues and automatically correlate them with infrastructure metrics for scaling decisions. Part of the AWS obse…
- name: Prometheus HTTP API
  description: Prometheus is the de-facto open-source monitoring and alerting toolkit for cloud-native applications and a CNCF graduate project. The Prometheus HTTP API provides access to time series data, metadata, and administrative functions used exte…
- name: Grafana HTTP API
  description: Grafana is the open-source platform for monitoring and observability, providing a REST HTTP API for managing dashboards, data sources, users, and alerts. Widely used alongside Prometheus for scalability metrics visualization and alerting w…
links:
- type: GitHubOrganization
  url: https://github.com/kedacore
- type: CNCF Landscape
  url: https://landscape.cncf.io/card-mode?category=auto-scaling
- type: Blog
  url: https://kubernetes.io/blog/
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-scaling-policy-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-load-balancer-schema.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-ld/scalability-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/vocabulary/scalability-vocabulary.yml
provider_count: 76
providers:
- slug: new-relic
  name: New Relic
  description: New Relic provides observability platform APIs for monitoring, analyzing, and optimizing your entire software stack with real-time insights into applications, infrastructure, and customer experience.
  api_count: 5
  score_band: exemplar
  score_composite: 68.1
  shared: 3
- slug: amazon-elastic-load-balancing
  name: Amazon Elastic Load Balancing
  description: Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for…
  api_count: 1
  score_band: strong
  score_composite: 65.0
  shared: 3
- slug: ibm
  name: IBM
  description: A collection of IBM's public APIs and developer resources.
  api_count: 1
  score_band: strong
  score_composite: 62.6
  shared: 3
- slug: haproxy
  name: HAProxy
  description: HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It exposes a Data Plane API for dynamic configuration management and a stats socket for r…
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 3
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 2
  score_band: exemplar
  score_composite: 73.3
  shared: 2
- slug: synadia-communications
  name: Synadia Communications
  description: Synadia Communications, Inc. is the creator and primary maintainer of NATS.io, the CNCF connectivity and messaging system, and sells the commercial platform built on it. Its products are Synadia Cloud (fully managed, globally distributed N…
  api_count: 2
  score_band: strong
  score_composite: 65.6
  shared: 2
- slug: amazon-ec2
  name: Amazon EC2
  description: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with complete control over your computing resources.
  api_count: 1
  score_band: strong
  score_composite: 62.8
  shared: 2
- slug: facets
  name: Facets
  description: Facets is an AI-native SDLC orchestrator and platform-engineering control plane that unifies infrastructure provisioning, CI/CD and configuration management into a single declarative blueprint model, so product teams get self-serve, drift-…
  api_count: 2
  score_band: strong
  score_composite: 61.0
  shared: 2
- slug: google-cloud-platform
  name: Google Cloud Platform
  description: Google Cloud Platform enables developers to build, test, and deploy applications on Google's highly-scalable and reliable infrastructure.
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 2
- slug: oracle-partitioning
  name: Oracle Partitioning
  description: Oracle Partitioning is a licensed option of Oracle Database Enterprise Edition that divides large tables and indexes into smaller, independently manageable segments called partitions, accessed transparently through the table name. It deliv…
  api_count: 1
  score_band: strong
  score_composite: 59.0
  shared: 2
- slug: amazon-global-accelerator
  name: Amazon Global Accelerator
  description: Amazon Global Accelerator is a networking service that improves the performance and availability of applications with local or global users. It provides static IP addresses that act as a fixed entry point to your applications and uses the…
  api_count: 1
  score_band: strong
  score_composite: 57.0
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
- slug: platform.sh
  name: Platform.sh
  description: Platform.sh is the container-based Platform-as-a-Service (PaaS) founded in 2010 and headquartered in Paris and San Francisco, best known for Git-driven deployments in which a single push plus a few YAML files provisions an entire cluster o…
  api_count: 3
  score_band: strong
  score_composite: 54.7
  shared: 2
- slug: microsoft-azure-virtual-machines
  name: Azure Virtual Machines
  description: Azure Virtual Machines (VMs) is one of several types of on-demand, scalable computing resources that Azure offers. VMs give you the flexibility of virtualization without having to buy and maintain physical hardware.
  api_count: 1
  score_band: strong
  score_composite: 54.4
  shared: 2
- slug: scale3
  name: Scale3
  description: Scale3 Labs is a modern observability and infrastructure platform for Web3 and generative AI. Its Web3 products (Autopilot, Nodepilot and Blockchain Intelligence) let node operators and validators deploy, monitor, log and alert on blockcha…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: vmware
  name: VMware
  description: Collection of VMware APIs for cloud infrastructure, virtualization, and management solutions including vSphere, NSX, vCloud Director, Tanzu, and Aria operations.
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 2
- slug: gameye
  name: Gameye
  description: Gameye is a managed game server orchestration platform for multiplayer game studios, founded in 2017 in Rotterdam (Gameye B.V.). It runs dedicated, containerized game servers across bare metal, cloud, and edge providers behind a single RES…
  api_count: 1
  score_band: developing
  score_composite: 51.9
  shared: 2
- slug: scaleway
  name: Scaleway
  description: Scaleway is a European cloud provider offering a full suite of compute, storage, networking, AI, and serverless infrastructure services. Scaleway provides a comprehensive REST API for programmatic management of all cloud resources includin…
  api_count: 10
  score_band: developing
  score_composite: 51.8
  shared: 2
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 2
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: render
  name: Render
  description: Render is a cloud platform for building and running applications and websites with automatic Git-based deployments. It provides managed infrastructure for web services, static sites, background workers, cron jobs, private services, Postgre…
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 2
- slug: openbao
  name: OpenBao
  description: OpenBao is an open source, community-driven identity-based secrets and encryption management system, forked from HashiCorp Vault in 2023 and governed by the Linux Foundation as a sandbox project of the Open Source Security Foundation (Open…
  api_count: 1
  score_band: developing
  score_composite: 49.6
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
- slug: termius
  name: Termius
  description: Termius is a modern, cross-platform SSH client for DevOps professionals, network engineers, and infrastructure teams, available on Windows, macOS, Linux, iOS, iPadOS, and Android. It provides secure remote access with encrypted team vaults…
  api_count: 2
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: virtual-instruments
  name: Virtana (Virtual Instruments)
  description: Virtana (formerly Virtual Instruments) is an AI-powered hybrid infrastructure observability company whose platform monitors and optimizes performance, cost, and risk across on-premises, colocation, and cloud environments. The platform span…
  api_count: 3
  score_band: developing
  score_composite: 47.7
  shared: 2
- slug: tensorwave
  name: TensorWave
  description: TensorWave is a Las Vegas-headquartered AI cloud provider that builds and operates bare-metal GPU infrastructure exclusively on AMD Instinct accelerators (MI300X, MI325X, MI355X and MI455X) with AMD's open ROCm software stack. The company…
  api_count: 1
  score_band: developing
  score_composite: 46.9
  shared: 2
- slug: cast-ai
  name: CAST AI
  description: CAST AI is an Application Performance Automation (APA) platform for Kubernetes that automates cost optimization, autoscaling, workload rightsizing, GPU/LLM workload placement, spot instance selection, and security posture analysis. The pla…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: netdata
  name: Netdata
  description: Netdata is a real-time infrastructure monitoring and observability platform that collects per-second metrics from physical servers, virtual machines, cloud deployments, Kubernetes clusters, and IoT devices. It provides a REST API for query…
  api_count: 1
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: oxide-computer
  name: Oxide
  description: 'Oxide Computer Company builds a rack-scale cloud computer: integrated server sleds (Gimlet), a rack-level switch (Sidecar), Oxide''s own illumos distribution (Helios), the Propolis/bhyve hypervisor and the Crucible distributed block store,…'
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
---
