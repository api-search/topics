---
layout: topic
slug: scalable-services
name: Scalable Services
kind: topic
description: A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that enable services to scale horizontally and vertically. Relevant to platform engineers, cloud architects, and backend developers building high-traffic, distributed systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalable-services.png
tags:
- API Gateway
- Cloud-Native
- Containers
- Distributed Systems
- High Availability
- Kubernetes
- Load Balancing
- Microservices
- Scalable Architecture
- Serverless
- Service Mesh
repo: https://github.com/api-evangelist/scalable-services
api_count: 14
apis:
- name: Envoy Admin API
  description: Envoy Proxy's administration API for inspecting and modifying Envoy runtime configuration, stats, clusters, and listeners. Envoy is the foundational data plane for many service mesh and API gateway deployments.
  url: https://www.envoyproxy.io/docs/envoy/latest/operations/admin
- name: Istio API
  description: Istio's configuration APIs define traffic management, security policy, and observability for microservice meshes. Expressed as Kubernetes CRDs (VirtualService, DestinationRule, Gateway, etc.).
  url: https://istio.io/latest/docs/reference/config/
- name: AWS Lambda API
  description: Amazon Web Services Lambda API for creating, managing, invoking, and monitoring serverless functions. Core to event-driven, auto-scaling architectures.
  url: https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html
- name: Kong Admin API
  description: Kong Gateway's RESTful Admin API for managing services, routes, plugins, consumers, upstreams, and certificates. Kong is a widely deployed open-source API gateway for scalable API management.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Prometheus HTTP API
  description: Prometheus exposes an HTTP API for querying metrics, metadata, and alerting rules. Essential for observability and autoscaling decisions in scalable service architectures.
  url: https://prometheus.io/docs/prometheus/latest/querying/api/
- name: Knative API
  description: Knative provides Kubernetes-based platform APIs for deploying and scaling event-driven serverless workloads. Includes Knative Serving (scale-to-zero) and Knative Eventing (event sourcing and routing).
  url: https://knative.dev/docs/
- name: gRPC Reflection API
  description: gRPC server reflection provides information about publicly-accessible gRPC services on a server, enabling discovery and dynamic invocation. gRPC is widely used for high-performance inter-service communication in scalable microservice archi…
  url: https://grpc.io/docs/
- name: Scalable Services ConfigMaps API
  description: The ConfigMaps API from Scalable Services — 1 operation(s) for configmaps.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services Namespaces API
  description: The Namespaces API from Scalable Services — 2 operation(s) for namespaces.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services Nodes API
  description: The Nodes API from Scalable Services — 2 operation(s) for nodes.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services PersistentVolumes API
  description: The PersistentVolumes API from Scalable Services — 1 operation(s) for persistentvolumes.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services Pods API
  description: The Pods API from Scalable Services — 3 operation(s) for pods.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services Secrets API
  description: The Secrets API from Scalable Services — 1 operation(s) for secrets.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- name: Scalable Services API
  description: The Services API from Scalable Services — 2 operation(s) for services.
  url: https://kubernetes.io/docs/reference/kubernetes-api/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/scalable-services/blob/main/agentic-access/scalable-services-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/scalable-services/blob/main/security/scalable-services-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/scalable-services/blob/main/security/scalable-services-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/scalable-services/blob/main/authentication/scalable-services-authentication.yml
- type: Documentation
  url: https://kubernetes.io/docs/concepts/architecture/
- type: Guide
  url: https://microservices.io/patterns/index.html
- type: Guide
  url: https://www.cncf.io/projects/
- type: Guide
  url: https://istio.io/latest/about/service-mesh/
- type: Guide
  url: https://www.envoyproxy.io/learn/service-mesh
- type: JSONSchema
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-schema/scalable-services-service-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-structure/scalable-services-service-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-services/blob/main/json-ld/scalable-services-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/scalable-services/blob/main/vocabulary/scalable-services-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kubernetes-hpa-example.json
- type: Examples
  url: https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kong-plugin-example.json
provider_count: 214
providers:
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 37.1
  shared: 5
- slug: restful-microservices
  name: RESTful Microservices
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services that communicate via REST APIs using HTTP methods and standard web protocols. This collection covers RESTful micros…
  api_count: 0
  score_band: minimal
  score_composite: 8.9
  shared: 5
- slug: solo-io
  name: Solo.io
  description: Solo.io is a cloud-native application-networking company founded in 2017 that builds enterprise and open-source API gateways, service mesh, and agentic-AI infrastructure. Its products include Kgateway Enterprise (formerly Gloo Gateway), an…
  api_count: 5
  score_band: strong
  score_composite: 62.4
  shared: 4
- slug: azure-container-apps
  name: Azure Container Apps
  description: Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developers to deploy containers without managing…
  api_count: 1
  score_band: strong
  score_composite: 61.6
  shared: 4
- slug: gloo
  name: Gloo
  description: Gloo is Solo.io's family of open-source and enterprise API gateway, service mesh and developer portal products, built on Envoy Proxy and Istio and delivered as software the customer runs in their own Kubernetes clusters rather than as a ho…
  api_count: 8
  score_band: strong
  score_composite: 57.1
  shared: 4
- slug: envoy-gateway
  name: Envoy Gateway
  description: Envoy Gateway is a CNCF project that manages Envoy Proxy as a standalone or Kubernetes-based application gateway. It implements the Kubernetes Gateway API and extends it with its own API group, gateway.envoyproxy.io, whose eight Custom Res…
  api_count: 3
  score_band: developing
  score_composite: 42.6
  shared: 4
- slug: vmware-tanzu
  name: VMware Tanzu
  description: VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu…
  api_count: 2
  score_band: thin
  score_composite: 36.4
  shared: 4
- slug: quarkus
  name: Quarkus
  description: Quarkus is a Kubernetes-native Java framework tailored for GraalVM and OpenJDK HotSpot, designed to build cloud-native microservices and serverless applications with fast startup times and low memory footprint.
  api_count: 1
  score_band: thin
  score_composite: 26.4
  shared: 4
- slug: open-service-mesh
  name: Open Service Mesh
  description: Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh built on Envoy and the Service Mesh Interface (SMI) specification. OSM provides traffic shifting, mutual TLS, access control, observability, and automatic side…
  api_count: 1
  score_band: emerging
  score_composite: 24.5
  shared: 4
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 24
  score_band: exemplar
  score_composite: 71.1
  shared: 3
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and secu…
  api_count: 1
  score_band: exemplar
  score_composite: 71.0
  shared: 3
- slug: scaleway
  name: Scaleway
  description: Scaleway is a European cloud provider offering a full suite of compute, storage, networking, AI, and serverless infrastructure services. Scaleway provides a comprehensive REST API for programmatic management of all cloud resources includin…
  api_count: 10
  score_band: developing
  score_composite: 51.8
  shared: 3
- slug: aws-app-runner
  name: AWS App Runner
  description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances t…
  api_count: 1
  score_band: developing
  score_composite: 51.2
  shared: 3
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 51.2
  shared: 3
- slug: knative
  name: Knative
  description: Knative is a CNCF graduated platform that extends Kubernetes to provide serverless capabilities. It consists of Serving for deploying and scaling serverless workloads with automatic scale-to-zero, and Eventing for building event-driven arc…
  api_count: 2
  score_band: developing
  score_composite: 49.9
  shared: 3
- slug: apache-apisix
  name: Apache APISIX
  description: Apache APISIX is a dynamic, real-time, high-performance cloud-native API gateway built on NGINX and etcd, developed by the Apache Software Foundation. It supports Lua and multi-language plugins for traffic management, authentication, obser…
  api_count: 2
  score_band: developing
  score_composite: 48.8
  shared: 3
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 3
- slug: amazon-fargate
  name: Amazon Fargate
  description: Amazon Fargate is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. Fargate removes the need to provision and manage servers, letting you specify and pay for resources per application, and improves…
  api_count: 6
  score_band: developing
  score_composite: 47.6
  shared: 3
- slug: envoy
  name: Envoy
  description: Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the d…
  api_count: 3
  score_band: developing
  score_composite: 45.3
  shared: 3
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 2
  score_band: developing
  score_composite: 43.6
  shared: 3
- slug: haproxy
  name: HAProxy
  description: HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It exposes a Data Plane API for dynamic configuration management and a stats socket for r…
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 3
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 1
  score_band: developing
  score_composite: 43.2
  shared: 3
- slug: aqua-security
  name: Aqua Security
  description: Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and compliance enforcement.
  api_count: 8
  score_band: developing
  score_composite: 41.6
  shared: 3
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium proje…
  api_count: 2
  score_band: developing
  score_composite: 40.7
  shared: 3
- slug: google-cloud-service-mesh
  name: Google Cloud Service Mesh
  description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane…
  api_count: 13
  score_band: thin
  score_composite: 38.2
  shared: 3
- slug: veritas-cluster
  name: Veritas Cluster Server
  description: APIs for managing and monitoring Veritas Cluster Server (VCS) and InfoScale infrastructure, providing high availability, disaster recovery, and storage management capabilities across on-premises and containerized environments.
  api_count: 8
  score_band: thin
  score_composite: 38.2
  shared: 3
- slug: youki
  name: Youki
  description: youki is an open source container runtime written in Rust that implements the OCI runtime specification as a memory-safe alternative to runc, with rootless container support, cgroups v1 and v2, seccomp filtering, and systemd integration. M…
  api_count: 2
  score_band: thin
  score_composite: 38.2
  shared: 3
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 37.7
  shared: 3
- slug: google-kubernetes-engine
  name: Google Kubernetes Engine
  description: Google Kubernetes Engine (GKE) is a managed Kubernetes service on Google Cloud that provides a production-ready environment for deploying, managing, and scaling containerized applications. It offers autopilot and standard modes, built-in s…
  api_count: 5
  score_band: thin
  score_composite: 37.1
  shared: 3
- slug: spring-cloud-gateway
  name: Spring Cloud Gateway
  description: Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit break…
  api_count: 1
  score_band: thin
  score_composite: 36.9
  shared: 3
---
