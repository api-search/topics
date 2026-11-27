---
layout: topic
slug: restful-microservices
name: RESTful Microservices
kind: topic
description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services that communicate via REST APIs using HTTP methods and standard web protocols. This collection covers RESTful microservices patterns, tools, service mesh technologies, API gateways, observability, and the ecosystem of frameworks and platforms for building, deploying, and scaling microservice architectures.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/restful-microservices.png
tags:
- Architecture
- Distributed Systems
- Microservices
- REST
- Kubernetes
- Service Mesh
- Cloud-Native
repo: https://github.com/api-evangelist/restful-microservices
api_count: 0
apis: []
links:
- type: BlogRSS
  url: https://microservices.io/feed.xml
- type: DomainSecurity
  url: https://artifacts.apis.io/restful-microservices/security/restful-microservices-domain-security.yml
- type: Website
  url: https://microservices.io/
- type: 12 Factor App
  url: https://12factor.net/
- type: CNCF Cloud Native Landscape
  url: https://landscape.cncf.io/
- type: Kubernetes Documentation
  url: https://kubernetes.io/docs/
- type: Istio Service Mesh
  url: https://istio.io/
- type: Kong API Gateway
  url: https://konghq.com/
- type: OpenTelemetry
  url: https://opentelemetry.io/
- type: Prometheus Monitoring
  url: https://prometheus.io/
- type: gRPC Framework
  url: https://grpc.io/
- type: Spring Cloud
  url: https://spring.io/cloud
- type: Open Liberty RESTful Microservices
  url: https://openliberty.io/docs/latest/rest-microservices.html
provider_count: 136
providers:
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 34.5
  shared: 4
- slug: open-service-mesh
  name: Open Service Mesh
  description: Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh built on Envoy and the Service Mesh Interface (SMI) specification. OSM provides traffic shifting, mutual TLS, access control, observability, and automatic side…
  api_count: 1
  score_band: emerging
  score_composite: 21.9
  shared: 4
- slug: solo-io
  name: Solo.io
  description: Solo.io is a cloud-native application-networking company founded in 2017 that builds enterprise and open-source API gateways, service mesh, and agentic-AI infrastructure. Its products include Kgateway Enterprise (formerly Gloo Gateway), an…
  api_count: 5
  score_band: strong
  score_composite: 62.3
  shared: 3
- slug: gloo
  name: Gloo
  description: Gloo is Solo.io's family of open-source and enterprise API gateway, service mesh and developer portal products, built on Envoy Proxy and Istio and delivered as software the customer runs in their own Kubernetes clusters rather than as a ho…
  api_count: 4
  score_band: strong
  score_composite: 60.4
  shared: 3
- slug: google-cloud-service-mesh
  name: Google Cloud Service Mesh
  description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane…
  api_count: 4
  score_band: strong
  score_composite: 59.7
  shared: 3
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 52.3
  shared: 3
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 3
- slug: envoy-gateway
  name: Envoy Gateway
  description: Envoy Gateway is a CNCF project that manages Envoy Proxy as a standalone or Kubernetes-based application gateway. It implements the Kubernetes Gateway API and extends it with its own API group, gateway.envoyproxy.io, whose eight Custom Res…
  api_count: 3
  score_band: developing
  score_composite: 41.9
  shared: 3
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium proje…
  api_count: 2
  score_band: developing
  score_composite: 41.7
  shared: 3
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 1
  score_band: developing
  score_composite: 40.4
  shared: 3
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, mes…
  api_count: 3
  score_band: developing
  score_composite: 40.2
  shared: 3
- slug: linkerd
  name: Linkerd
  description: Service mesh without the mess. Linkerd adds security, observability, and reliability to any Kubernetes cluster without the complexity of bloat of other meshes.
  api_count: 3
  score_band: thin
  score_composite: 37.1
  shared: 3
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 36.5
  shared: 3
- slug: ambient-mesh
  name: Ambient Mesh
  description: Ambient Mesh is a sidecar-less service mesh architecture built on Istio that simplifies microservices communication, enhances zero-trust security, and improves observability without requiring sidecar proxy injection. It uses a shared per-n…
  api_count: 1
  score_band: thin
  score_composite: 33.8
  shared: 3
- slug: vmware-tanzu
  name: VMware Tanzu
  description: VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu…
  api_count: 2
  score_band: thin
  score_composite: 32.0
  shared: 3
- slug: meshery
  name: Meshery
  description: Meshery is the cloud native manager for Kubernetes and cloud native infrastructure. It is an extensible, self-service engineering platform that enables collaborative design, lifecycle and performance management of cloud native applications…
  api_count: 0
  score_band: thin
  score_composite: 30.5
  shared: 3
- slug: quarkus
  name: Quarkus
  description: Quarkus is a Kubernetes-native Java framework tailored for GraalVM and OpenJDK HotSpot, designed to build cloud-native microservices and serverless applications with fast startup times and low memory footprint.
  api_count: 1
  score_band: thin
  score_composite: 27.7
  shared: 3
- slug: vineyard
  name: Vineyard
  description: Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyar…
  api_count: 1
  score_band: thin
  score_composite: 26.9
  shared: 3
- slug: getenroute
  name: Saaras
  description: Saaras provides cloud‑native API gateway and service‑mesh solutions built on Kubernetes. Their EnRoute Gateway offers high‑performance traffic management, security, observability, and dynamic routing for modern cloud applications. Saaras a…
  api_count: 4
  score_band: emerging
  score_composite: 20.1
  shared: 3
- slug: octarine
  name: Octarine
  description: Octarine was a cloud-native application security startup that built a security platform for Kubernetes and service-mesh environments, providing runtime visibility, policy enforcement, and threat detection for containerized workloads and mi…
  api_count: 0
  score_band: minimal
  score_composite: 2.6
  shared: 3
- slug: restful-services
  name: RESTful Services
  description: Representational State Transfer (REST) services are web services built using the REST architectural style, which uses stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. RESTful servi…
  api_count: 5
  score_band: null
  score_composite: 0
  shared: 3
- slug: akuity
  name: Akuity
  description: 'Akuity is the enterprise software delivery company founded by the creators of Argo CD and Kargo. The Akuity Platform is its commercial, fully-managed offering: hosted, enterprise-grade Argo CD control planes for GitOps continuous delivery,…'
  api_count: 8
  score_band: exemplar
  score_composite: 73.7
  shared: 2
- slug: amazon-vpc-lattice
  name: Amazon VPC Lattice
  description: Amazon VPC Lattice is an application networking service that consistently connects, monitors, and secures communications between your services, helping you to improve productivity so that your developers can focus on building features that…
  api_count: 73
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 4
  score_band: exemplar
  score_composite: 70.5
  shared: 2
- slug: azure-container-apps
  name: Azure Container Apps
  description: Azure Container Apps is a serverless container service for running microservices and containerized applications with built-in autoscaling, traffic splitting, and Dapr integration. It enables developers to deploy containers without managing…
  api_count: 3
  score_band: exemplar
  score_composite: 68.3
  shared: 2
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 7
  score_band: exemplar
  score_composite: 67.7
  shared: 2
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and secu…
  api_count: 1
  score_band: exemplar
  score_composite: 67.3
  shared: 2
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 3
  score_band: exemplar
  score_composite: 66.7
  shared: 2
- slug: okteto
  name: Okteto
  description: 'Okteto is a development-environment platform built on Kubernetes. Its site says it "gives coding agents production-like environments to verify their work": isolated, full-stack environments that run on your own infrastructure. Teams use it…'
  api_count: 1
  score_band: strong
  score_composite: 65.3
  shared: 2
- slug: grafana-loki
  name: Grafana Loki
  description: Grafana Loki is Grafana Labs' open source log aggregation system — "like Prometheus, but for logs." Rather than full-text indexing log contents, Loki indexes only a small set of labels per log stream and stores the compressed lines in obje…
  api_count: 3
  score_band: strong
  score_composite: 64.9
  shared: 2
---
