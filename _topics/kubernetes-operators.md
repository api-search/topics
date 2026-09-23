---
layout: topic
slug: kubernetes-operators
name: Kubernetes Operators
kind: topic
description: Kubernetes Operators are a method of packaging, deploying, and managing Kubernetes applications that extend the Kubernetes API to create, configure, and manage instances of complex applications on behalf of a Kubernetes user.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/kubernetes-operators.png
tags:
- Automation
- Cloud-Native
- DevOps
- Infrastructure
- Kubernetes
repo: https://github.com/api-evangelist/kubernetes-operators
api_count: 11
apis:
- name: Kubernetes Operators
  description: Kubernetes Operators extend the Kubernetes API for managing complex stateful applications using custom resources and controllers. An Operator encodes the operational knowledge of a domain expert into software that automates the deployment,…
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Operator SDK
  description: The Operator SDK is a framework for building Kubernetes Operators in Go, Ansible, or Helm. It provides high-level APIs, abstractions, scaffolding tools, and CLI commands that simplify writing operator logic and integrating with the Operato…
  url: https://sdk.operatorframework.io/
- name: OperatorHub
  description: OperatorHub.io is a community registry of Kubernetes Operators that can be discovered and installed via the Operator Lifecycle Manager. It provides a catalog of operators across categories including databases, monitoring, security, and net…
  url: https://operatorhub.io/
- name: Controller-Runtime
  description: controller-runtime is a set of Go libraries for building Kubernetes controllers and operators. It is used by both Kubebuilder and Operator SDK and provides core abstractions including Manager, Client, Cache, and Reconciler interfaces for b…
  url: https://github.com/kubernetes-sigs/controller-runtime
- name: Kubernetes Operators Catalog Source API
  description: CatalogSource resources pointing to operator registries (gRPC or ConfigMap-backed) that OLM queries for available operators and versions.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators Cluster Service Version API
  description: ClusterServiceVersion resources representing the installed operator version with its deployment spec, RBAC rules, and owned CRDs.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators CRD Status API
  description: Status subresource operations for CRDs reporting acceptance and establishment conditions.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators Custom Resource Definitions API
  description: CustomResourceDefinition resources that extend the Kubernetes API with new resource types, schemas, and versioning for operator-managed objects.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators Install Plan API
  description: InstallPlan resources listing the set of resources OLM will create to install or upgrade an operator, pending admin approval if required.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators Operator Group API
  description: OperatorGroup resources defining which namespaces operators installed in the group are allowed to watch and manage resources in.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- name: Kubernetes Operators Subscription API
  description: Subscription resources expressing intent to install an operator from a channel, with automatic or manual update approval.
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
links:
- type: IssueTracker
  url: https://github.com/operator-framework/operator-sdk/issues
- type: Releases
  url: https://github.com/operator-framework/operator-sdk/releases
- type: SecurityPolicy
  url: https://github.com/operator-framework/operator-sdk/blob/master/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/operator-framework/operator-sdk/blob/master/code-of-conduct.md
- type: ContributionGuide
  url: https://github.com/operator-framework/operator-sdk/blob/master/CONTRIBUTING.MD
- type: License
  url: https://github.com/operator-framework/operator-sdk/blob/master/LICENSE
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/kubernetes-operators/blob/main/security/kubernetes-operators-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/kubernetes-operators/blob/main/security/kubernetes-operators-domain-security.yml
- type: Website
  url: https://kubernetes.io
- type: Documentation
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/
- type: GettingStarted
  url: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
- type: GitHubOrganization
  url: https://github.com/operator-framework
- type: GitHubRepository
  url: https://github.com/operator-framework/operator-sdk
- type: Blog
  url: https://kubernetes.io/blog/
- type: Community
  url: https://kubernetes.io/community/
- type: ChangeLog
  url: https://kubernetes.io/releases/
- type: JSONSchema
  url: https://github.com/api-evangelist/kubernetes-operators/blob/main/json-schema/kubernetes-operator-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/kubernetes-operators/blob/main/json-ld/kubernetes-operators-context.jsonld
provider_count: 210
providers:
- slug: facets
  name: Facets
  description: Facets is an AI-native SDLC orchestrator and platform-engineering control plane that unifies infrastructure provisioning, CI/CD and configuration management into a single declarative blueprint model, so product teams get self-serve, drift-…
  api_count: 2
  score_band: strong
  score_composite: 61.0
  shared: 4
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 2
  score_band: developing
  score_composite: 50.5
  shared: 4
- slug: coreos
  name: CoreOS
  description: CoreOS was a San Francisco-based container infrastructure company founded in 2013 that built a lightweight, automatically-updating Linux distribution (Container Linux, originally CoreOS Linux) and a family of now-foundational cloud-native…
  api_count: 0
  score_band: minimal
  score_composite: 5.3
  shared: 4
- slug: heptio
  name: Heptio
  description: Heptio was a Seattle-based cloud-native software company founded in 2016 by Craig McLuckie and Joe Beda, two of the original co-creators of Kubernetes, to help enterprises adopt and operate Kubernetes. It built a suite of widely used open-…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: akuity
  name: Akuity
  description: 'Akuity is the enterprise software delivery company founded by the creators of Argo CD and Kargo. The Akuity Platform is its commercial, fully-managed offering: hosted, enterprise-grade Argo CD control planes for GitOps continuous delivery,…'
  api_count: 8
  score_band: exemplar
  score_composite: 71.5
  shared: 3
- slug: nuon
  name: Nuon
  description: Nuon is a Bring Your Own Cloud (BYOC) continuous-delivery platform for software vendors. It lets vendors package existing applications — Terraform, Pulumi, Helm charts, Kubernetes manifests, and container images — and deploy them into thei…
  api_count: 2
  score_band: strong
  score_composite: 55.5
  shared: 3
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: developing
  score_composite: 51.3
  shared: 3
- slug: choreo
  name: Choreo
  description: WSO2 Choreo is an enterprise-grade Internal Developer Platform (IDP) and application orchestration platform that helps organizations build, deploy, manage, and observe APIs, microservices, integrations, and AI applications across multi-clo…
  api_count: 3
  score_band: developing
  score_composite: 47.7
  shared: 3
- slug: runwhen
  name: RunWhen
  description: RunWhen is an AI platform for building safe-for-production agents that triage alerts, remediate infrastructure, analyze cost, and answer questions about production systems. Engineering teams compose reusable "Skills" (CodeBundles) into age…
  api_count: 1
  score_band: developing
  score_composite: 45.1
  shared: 3
- slug: porter
  name: Porter
  description: A package manager for Kubernetes that uses Cloud Native Application Bundles (CNAB) to package and deploy applications along with their dependencies and configuration.
  api_count: 1
  score_band: developing
  score_composite: 44.5
  shared: 3
- slug: helm
  name: Helm
  description: Package manager for Kubernetes that helps you define, install, and upgrade complex Kubernetes applications using charts. Helm uses a packaging format called charts, which are collections of files that describe a related set of Kubernetes r…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: sensu
  name: Sensu
  description: Sensu (Sensu by Sumo Logic) is an observability pipeline that delivers monitoring as code across multi-cloud and hybrid environments. Sensu Go codifies monitoring workflows into declarative, versionable configuration and exposes a backend…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 3
- slug: calyptia
  name: Calyptia
  description: Calyptia builds Calyptia Cloud (Telemetry Pipeline) and Calyptia Core, a commercial management plane for Fluent Bit — the widely deployed open-source agent and processor for logs, metrics and traces. The Calyptia Cloud API lets teams creat…
  api_count: 1
  score_band: thin
  score_composite: 35.0
  shared: 3
- slug: duplo-cloud
  name: Duplo Cloud
  description: DuploCloud is an AI-native DevOps platform that automates cloud infrastructure provisioning, security, and compliance across AWS, Azure, GCP, and Kubernetes. Its ARMOR agent runtime lets teams build and run AI DevOps agents that create tic…
  api_count: 0
  score_band: thin
  score_composite: 33.2
  shared: 3
- slug: kubeark
  name: Kubeark
  description: 'Kubeark is an enterprise orchestration and AI automation platform that standardizes system integration across hybrid estates. It combines three surfaces: workflow automation, where technical teams and end users build language-agnostic work…'
  api_count: 0
  score_band: thin
  score_composite: 32.8
  shared: 3
- slug: kasten
  name: Kasten
  description: Veeam Kasten (formerly Kasten K10) is an enterprise-grade, Kubernetes-native data protection platform. It delivers backup and recovery, disaster recovery, application mobility, ransomware resilience, and virtual-machine (KubeVirt) protecti…
  api_count: 0
  score_band: thin
  score_composite: 26.4
  shared: 3
- slug: kagent
  name: kagent
  description: kagent is an open-source framework for running AI agents in Kubernetes, automating complex DevOps operations and troubleshooting tasks with intelligent workflows. It is a Cloud Native Computing Foundation sandbox project that brings agenti…
  api_count: 1
  score_band: emerging
  score_composite: 24.6
  shared: 3
- slug: niteshift
  name: Niteshift
  description: Niteshift is the full-stack cloud for coding agents. Engineering teams define their dev environment, tools, and policies once, then run frontier or open-source coding agents (Claude Code, Codex, Cursor, OpenCode, Pi) inside fully configure…
  api_count: 0
  score_band: emerging
  score_composite: 24.0
  shared: 3
- slug: tintri
  name: Tintri
  description: 'Tintri, now part of DDN, builds intelligent enterprise data-management and storage infrastructure: the VMstore virtualization-aware storage platform, the Tintri Cloud Platform (TCP) and Cloud Engine (TCE), and the Tintri Global Center (TGC…'
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: k3s
  name: K3s
  description: K3s is a lightweight Kubernetes distribution designed for resource-constrained environments, edge computing, IoT devices, and CI/CD pipelines. K3s is a fully compliant Kubernetes distribution with a reduced memory footprint and simplified…
  api_count: 1
  score_band: emerging
  score_composite: 14.7
  shared: 3
- slug: metal3-io
  name: Metal3
  description: Metal3 (Metal Kubed) is a CNCF incubating project that provides bare metal host provisioning for Kubernetes. It leverages Ironic for hardware management and integrates with the Cluster API to enable Kubernetes-native lifecycle management o…
  api_count: 1
  score_band: emerging
  score_composite: 13.9
  shared: 3
- slug: operator-framework
  name: Operator Framework
  description: The Operator Framework is a CNCF incubating toolkit for building and managing Kubernetes Operators. It includes the Operator SDK for scaffolding and building operators using Go, Ansible, or Helm, the Operator Lifecycle Manager (OLM) for in…
  api_count: 2
  score_band: emerging
  score_composite: 13.4
  shared: 3
- slug: lablabee
  name: LabLabee
  description: LabLabee is an AI-powered enablement, testing and troubleshooting platform for telecom teams, positioning itself as "the Copilot for Telco Engineers." The platform delivers on-demand, hands-on labs, sandboxes, learning paths and skill test…
  api_count: 0
  score_band: emerging
  score_composite: 12.5
  shared: 3
- slug: komodor
  name: Komodor
  description: Komodor is an autonomous AI SRE platform for Kubernetes observability, troubleshooting, and operations across multiple clusters. The platform surfaces cluster events, deployment timelines, dependency maps, and remediation runbooks to help…
  api_count: 1
  score_band: emerging
  score_composite: 12.0
  shared: 3
- slug: weaveworks
  name: Weaveworks
  description: Weaveworks was the cloud-native company that coined the term "GitOps" and built the Weave family of open-source infrastructure tooling — Weave Net (multi-host container networking), Weave Scope (Docker/Kubernetes visualization and monitori…
  api_count: 0
  score_band: minimal
  score_composite: 8.7
  shared: 3
- slug: d2iq
  name: D2iQ
  description: D2iQ (formerly Mesosphere, maker of DC/OS) was an enterprise Kubernetes company whose flagship product, the D2iQ Kubernetes Platform (DKP), delivered production-grade Kubernetes cluster provisioning, day-2 operations, and application manag…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: diamanti
  name: Diamanti
  description: Diamanti was a San Jose, California infrastructure company (founded 2014) that built hyperconverged, bare-metal infrastructure purpose-built for containers and Kubernetes. Its flagship Ultima platform paired plug-and-play appliances with h…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 1
  score_band: exemplar
  score_composite: 80.2
  shared: 2
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 2
  score_band: exemplar
  score_composite: 73.3
  shared: 2
- slug: microsoft-azure-kubernetes-service
  name: Azure Kubernetes Service
  description: Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.
  api_count: 1
  score_band: exemplar
  score_composite: 72.2
  shared: 2
---
