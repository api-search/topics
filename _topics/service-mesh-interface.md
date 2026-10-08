---
layout: topic
slug: service-mesh-interface
name: Service Mesh Interface (SMI)
kind: topic
description: 'Service Mesh Interface (SMI) was a CNCF Sandbox specification that defined a standard, vendor-neutral set of Kubernetes Custom Resource Definitions (CRDs) for the most common service mesh capabilities: traffic policy, traffic telemetry, and traffic management. SMI''s stated mission was "a standard interface for service meshes on Kubernetes," letting operators write portable traffic policy that worked across Linkerd, Open Service Mesh, Consul Connect, Istio (via adapter), Traefik Mesh, Gloo Mesh, and others without lock-in. The specification reached v0.6.0 (January 2021 / republished January 2024) and defined four resource groups across distinct API versions: Traffic Access Control (v1alpha3), Traffic Specs (v1alpha4), Traffic Split (v1alpha4), and Traffic Metrics (v1alpha1). Active development ceased in July 2022 when the maintainers shifted focus to the Kubernetes SIG-Network GAMMA initiative inside the Gateway API project. CNCF formally archived SMI on October 3, 2023, with
  the GitHub org and all repositories marked read-only on October 20, 2023. The CNCF announcement stated: "the maintainers have decided to consolidate efforts on a service mesh under the auspices of GAMMA under the Kubernetes SIG Network initiative." Gateway API GAMMA reached GA in the Standard Channel with Gateway API v1.1.0 and is now the de facto Kubernetes standard for service mesh configuration, superseding SMI. This profile documents SMI as a historical/archived standard. It is preserved so consumers of the API Evangelist network can (a) recognize legacy SMI manifests still deployed in the wild, (b) understand the conceptual lineage that fed into Gateway API GAMMA, and (c) migrate off SMI to Gateway API.'
image: https://avatars.githubusercontent.com/u/59054423
tags:
- Service Mesh
- Kubernetes
- Traffic Policy
- Traffic Management
- Traffic Metrics
- Standards
- CNCF
- Archived
- Specification
- Custom Resource Definitions
repo: https://github.com/api-evangelist/service-mesh-interface
api_count: 4
apis:
- name: SMI Traffic Access Control
  description: 'Traffic Access Control defines the `TrafficTarget` resource, which associates a set of traffic rules with a service identity allocated to a group of pods. It is the authorization layer of SMI: which source identities may speak which protoc…'
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/apis/traffic-access/v1alpha3/traffic-access.md
- name: SMI Traffic Specs
  description: Traffic Specs describes a set of resources that allow users to specify how their traffic looks. It is used in concert with access control and other policies to concretely define what should happen to specific types of traffic as it flows t…
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/apis/traffic-specs/v1alpha4/traffic-specs.md
- name: SMI Traffic Split
  description: Traffic Split defines the `TrafficSplit` resource, which allows users to incrementally direct percentages of traffic between various services. It is the canonical SMI primitive for canary deployments, blue/green rollouts, and A/B testing a…
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/apis/traffic-split/v1alpha4/traffic-split.md
- name: SMI Traffic Metrics
  description: Traffic Metrics is "a resource that provides a common integration point for tools that can benefit by consuming metrics related to HTTP traffic." It is exposed as a Kubernetes APIService extension at `metrics.smi-spec.io/v1alpha1` and repo…
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/apis/traffic-metrics/v1alpha1/traffic-metrics.md
links:
- type: IssueTracker
  url: https://github.com/servicemeshinterface/smi-spec/issues
- type: Releases
  url: https://github.com/servicemeshinterface/smi-spec/releases
- type: ContributionGuide
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/service-mesh-interface/blob/main/security/service-mesh-interface-domain-security.yml
- type: Website
  url: https://smi-spec.io
- type: Specification
  url: https://github.com/servicemeshinterface/smi-spec
- type: GitHubOrg
  url: https://github.com/servicemeshinterface
- type: GitHubRepo
  url: https://github.com/servicemeshinterface/smi-spec
- type: License
  url: https://github.com/servicemeshinterface/smi-spec/blob/main/LICENSE
- type: Governance
  url: https://www.cncf.io
- type: ArchivalNotice
  url: https://www.cncf.io/blog/2023/10/03/cncf-archives-the-service-mesh-interface-smi-project/
- type: SuccessorSpecification
  url: https://gateway-api.sigs.k8s.io/mesh/gamma/
- type: SlackChannel
  url: https://cloud-native.slack.com
- type: SDKs
  url: https://github.com/servicemeshinterface/smi-sdk-go
- type: SDKs
  url: https://github.com/servicemeshinterface/smi-controller-sdk
- type: ReferenceImplementation
  url: https://github.com/servicemeshinterface/smi-metrics
- type: ReferenceImplementation
  url: https://github.com/servicemeshinterface/smi-adapter-istio
- type: ReferenceImplementation
  url: https://github.com/servicemeshinterface/istio-smi-controller
- type: KnownImplementation
  url: https://linkerd.io
- type: KnownImplementation
  url: https://openservicemesh.io
- type: KnownImplementation
  url: https://www.consul.io/docs/connect
- type: KnownImplementation
  url: https://traefik.io/traefik-mesh/
- type: KnownImplementation
  url: https://www.solo.io/products/gloo-mesh/
- type: KnownImplementation
  url: https://flagger.app
- type: KnownImplementation
  url: https://meshery.io
- type: KnownImplementation
  url: https://argoproj.github.io/rollouts/
- type: JSONSchema
  url: https://github.com/api-evangelist/service-mesh-interface/blob/main/./json-schema/
- type: JSONLD
  url: https://github.com/api-evangelist/service-mesh-interface/blob/main/./json-ld/service-mesh-interface-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/service-mesh-interface/blob/main/./vocabulary/service-mesh-interface-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/service-mesh-interface/blob/main/./examples/
provider_count: 63
providers:
- slug: crossplane
  name: Crossplane
  description: Crossplane is a graduated CNCF open-source Kubernetes add-on that transforms a cluster into a universal control plane for cloud infrastructure, services, and applications. Crossplane introduces custom resources including CompositeResourceD…
  api_count: 1
  score_band: developing
  score_composite: 47.2
  shared: 3
- slug: envoy-gateway
  name: Envoy Gateway
  description: Envoy Gateway is a CNCF project that manages Envoy Proxy as a standalone or Kubernetes-based application gateway. It implements the Kubernetes Gateway API and extends it with its own API group, gateway.envoyproxy.io, whose eight Custom Res…
  api_count: 3
  score_band: developing
  score_composite: 42.4
  shared: 3
- slug: linkerd
  name: Linkerd
  description: Service mesh without the mess. Linkerd adds security, observability, and reliability to any Kubernetes cluster without the complexity of bloat of other meshes.
  api_count: 3
  score_band: thin
  score_composite: 37.0
  shared: 3
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 36.4
  shared: 3
- slug: ambient-mesh
  name: Ambient Mesh
  description: Ambient Mesh is a sidecar-less service mesh architecture built on Istio that simplifies microservices communication, enhances zero-trust security, and improves observability without requiring sidecar proxy injection. It uses a shared per-n…
  api_count: 1
  score_band: thin
  score_composite: 35.2
  shared: 3
- slug: traefik-mesh
  name: Traefik Mesh
  description: Traefik Mesh (formerly Maesh) is a lightweight, non-invasive service mesh built on top of Traefik Proxy for Kubernetes. It provides automatic traffic management, observability, and security for microservices without requiring sidecar conta…
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 3
- slug: meshery
  name: Meshery
  description: Meshery is the cloud native manager for Kubernetes and cloud native infrastructure. It is an extensible, self-service engineering platform that enables collaborative design, lifecycle and performance management of cloud native applications…
  api_count: 0
  score_band: thin
  score_composite: 28.4
  shared: 3
- slug: nginx-service-mesh
  name: NGINX Service Mesh
  description: NGINX Service Mesh (NSM) is a service mesh from F5 NGINX powered by NGINX Plus, designed to manage container-to-container traffic in Kubernetes environments. It provides mTLS, traffic policies via the Service Mesh Interface (SMI), traffic…
  api_count: 1
  score_band: minimal
  score_composite: 10.3
  shared: 3
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and secu…
  api_count: 1
  score_band: strong
  score_composite: 66.3
  shared: 2
- slug: solo-io
  name: Solo.io
  description: Solo.io is a cloud-native application-networking company founded in 2017 that builds enterprise and open-source API gateways, service mesh, and agentic-AI infrastructure. Its products include Kgateway Enterprise (formerly Gloo Gateway), an…
  api_count: 5
  score_band: strong
  score_composite: 63.0
  shared: 2
- slug: gloo
  name: Gloo
  description: Gloo is Solo.io's family of open-source and enterprise API gateway, service mesh and developer portal products, built on Envoy Proxy and Istio and delivered as software the customer runs in their own Kubernetes clusters rather than as a ho…
  api_count: 8
  score_band: strong
  score_composite: 57.8
  shared: 2
- slug: buoyant
  name: Buoyant
  description: Buoyant is the creator of Linkerd, the CNCF-graduated service mesh for Kubernetes. Linkerd provides zero-trust security via mutual TLS, ultra-high availability with automated failover, and observability for microservices including AI/LLM w…
  api_count: 3
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: gsma
  name: GSMA
  description: The GSMA (GSM Association) is the London-headquartered global trade body for the mobile industry, representing roughly 750 mobile network operators and around 400 companies in the wider mobile ecosystem, and the organiser of MWC Barcelona.…
  api_count: 37
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: buildpacks-io
  name: Buildpacks Io
  description: Cloud Native Buildpacks (CNB) is a CNCF Graduated project (graduated 2026-07-17) that transforms application source code into OCI images that can run on any cloud. The v3 specification — Buildpack API 0.12, Platform API 0.15, and Distribut…
  api_count: 1
  score_band: developing
  score_composite: 53.4
  shared: 2
- slug: apache-apisix
  name: Apache APISIX
  description: Apache APISIX is a dynamic, real-time, high-performance cloud-native API gateway built on NGINX and etcd, developed by the Apache Software Foundation. It supports Lua and multi-language plugins for traffic management, authentication, obser…
  api_count: 2
  score_band: developing
  score_composite: 48.3
  shared: 2
- slug: argo
  name: Argo
  description: Argo is a collection of open-source Kubernetes-native tools for workflows, events, CI/CD, and progressive delivery. The project includes Argo Workflows (container-native workflow engine), Argo CD (declarative GitOps continuous delivery), A…
  api_count: 3
  score_band: developing
  score_composite: 47.6
  shared: 2
- slug: gloo-mesh
  name: Gloo Mesh
  description: Gloo Mesh is Solo.io's enterprise service mesh management platform, built on Istio and shipped as Kubernetes software you run in your own clusters. It provides multi-cluster and multi-mesh traffic management, security policy enforcement, w…
  api_count: 2
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: keda
  name: KEDA
  description: KEDA (Kubernetes Event Driven Autoscaling) is a CNCF graduated application autoscaler that drives scaling of any container in Kubernetes based on the number of events needing to be processed. It extends Kubernetes with custom resources for…
  api_count: 5
  score_band: developing
  score_composite: 46.9
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: argo-workflows
  name: Argo Workflows
  description: Argo Workflows is an open-source, container-native workflow engine for orchestrating parallel jobs on Kubernetes. It is a CNCF graduated project that allows you to define workflows where each step is a container, model multi-step workflows…
  api_count: 1
  score_band: developing
  score_composite: 45.1
  shared: 2
- slug: chaos-mesh
  name: Chaos Mesh
  description: Chaos Mesh is a CNCF graduated cloud-native chaos engineering platform that orchestrates chaos experiments on Kubernetes to test system resilience and reliability. It exposes Kubernetes Custom Resource Definitions (CRDs) for a wide range o…
  api_count: 2
  score_band: developing
  score_composite: 43.5
  shared: 2
- slug: rook
  name: Rook
  description: Rook is a CNCF graduated cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for Ceph distributed storage systems to natively integrate with cloud-native environments. It automates the deploymen…
  api_count: 1
  score_band: developing
  score_composite: 42.7
  shared: 2
- slug: coredns
  name: CoreDNS
  description: CoreDNS is a CNCF graduated DNS server written in Go that serves as the default DNS service for Kubernetes clusters. It is flexible and extensible through a plugin architecture, supporting DNS-based service discovery, forwarding, caching,…
  api_count: 2
  score_band: developing
  score_composite: 42.4
  shared: 2
- slug: kuma
  name: Kuma
  description: Kuma is a platform-agnostic open-source service mesh built on top of Envoy proxy. It provides universal connectivity, security, and observability for services and microservices running on any infrastructure including Kubernetes and VMs.
  api_count: 1
  score_band: developing
  score_composite: 42.0
  shared: 2
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium proje…
  api_count: 2
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: hami
  name: HAMi
  description: HAMi (Heterogeneous AI Computing Virtualization Middleware) is a CNCF incubating open-source project that brings device sharing, memory and core isolation, and topology-aware scheduling to heterogeneous AI accelerators on Kubernetes. It le…
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 2
- slug: scalable-inference-serving
  name: Scalable Inference Serving
  description: A collection of APIs, frameworks, and platforms for scalable machine learning model inference serving, deployment, and management. This includes the KServe Open Inference Protocol (the CNCF standard for model serving on Kubernetes), BentoM…
  api_count: 1
  score_band: developing
  score_composite: 39.5
  shared: 2
- slug: tetrate
  name: Tetrate
  description: Tetrate is an enterprise service mesh company that provides Tetrate Service Bridge (TSB), a multi-cluster, multi-cloud service mesh management platform built on Istio and Envoy Proxy. Tetrate offers management APIs for traffic, security, a…
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: google-cloud-service-mesh
  name: Google Cloud Service Mesh
  description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane…
  api_count: 13
  score_band: thin
  score_composite: 38.5
  shared: 2
- slug: argocd
  name: Argo CD
  description: Argo CD is a declarative GitOps continuous-delivery tool for Kubernetes, part of the CNCF Graduated Argo project. The argocd-server component exposes a gRPC and REST API used by the Web UI, the argocd CLI, and CI/CD systems. APIs cover app…
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
---
