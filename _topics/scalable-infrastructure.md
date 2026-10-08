---
layout: topic
slug: scalable-infrastructure
name: Scalable Infrastructure
kind: topic
description: A subject-matter collection covering APIs, tools, and platforms for building and managing scalable cloud infrastructure. This topic encompasses compute, storage, networking, container orchestration, infrastructure as code (IaC), monitoring, and the major cloud providers (AWS, Azure, GCP, DigitalOcean) that power modern scalable systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalable-infrastructure.png
tags:
- Cloud Infrastructure
- Compute
- DevOps
- Infrastructure as Code
- Kubernetes
- Networking
- Scalability
- Storage
repo: https://github.com/api-evangelist/scalable-infrastructure
api_count: 3
apis:
- name: Terraform Registry API
  description: The Terraform Registry API provides access to infrastructure-as-code (IaC) modules and providers. HashiCorp Terraform is the leading IaC tool for provisioning and managing cloud infrastructure in a declarative, version-controlled way. Crit…
- name: Pulumi Cloud API
  description: Pulumi is a modern infrastructure as code platform that uses general-purpose programming languages (TypeScript, Python, Go, C#, Java, YAML). The Pulumi Cloud API manages stacks, deployments, environments, and audit logs. Alternative to Ter…
- name: Scalable Infrastructure EC2 API
  description: The EC2 API from Scalable Infrastructure — 1 operation(s) for ec2.
links:
- type: RateLimits
  url: https://github.com/api-evangelist/scalable-infrastructure/blob/main/rate-limits/scalable-infrastructure-rate-limits.yml
- type: Plans
  url: https://github.com/api-evangelist/scalable-infrastructure/blob/main/plans/scalable-infrastructure-plans-pricing.yml
- type: CapabilityMap
  url: https://github.com/api-evangelist/scalable-infrastructure/blob/main/capabilities/scalable-infrastructure-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/scalable-infrastructure/blob/main/agentic-access/scalable-infrastructure-agentic-access.yml
- type: Authentication
  url: https://github.com/api-evangelist/scalable-infrastructure/blob/main/authentication/scalable-infrastructure-authentication.yml
- type: GitHubOrganization
  url: https://github.com/hashicorp
- type: CNCF Landscape
  url: https://landscape.cncf.io/card-mode?category=provisioning
- type: Blog
  url: https://www.cncf.io/blog/
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-compute-instance-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-schema/scalable-infrastructure-kubernetes-cluster-schema.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/json-ld/scalable-infrastructure-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/main/vocabulary/scalable-infrastructure-vocabulary.yml
provider_count: 155
providers:
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 3
  score_band: exemplar
  score_composite: 75.3
  shared: 4
- slug: intersight
  name: Cisco Intersight
  description: Cisco Intersight is Cisco's SaaS operations platform for UCS servers, HyperFlex clusters, Nexus fabrics, third-party storage and virtualization, covering provisioning, firmware lifecycle, workload optimization, telemetry and Kubernetes ser…
  api_count: 11
  score_band: strong
  score_composite: 59.7
  shared: 4
- slug: volumez
  name: Volumez
  description: Volumez is a SaaS data-infrastructure-as-a-service (DIaaS) company, founded in 2020, headquartered in the San Francisco Bay Area with R&D in Tel Aviv, that composes block and file storage directly out of cloud instance-local NVMe media ins…
  api_count: 1
  score_band: developing
  score_composite: 39.8
  shared: 4
- slug: duplo-cloud
  name: Duplo Cloud
  description: DuploCloud is an AI-native DevOps platform that automates cloud infrastructure provisioning, security, and compliance across AWS, Azure, GCP, and Kubernetes. Its ARMOR agent runtime lets teams build and run AI DevOps agents that create tic…
  api_count: 0
  score_band: thin
  score_composite: 34.5
  shared: 4
- slug: ibm
  name: IBM
  description: IBM offers solutions that protect identities and sensitive access for enterprise customers. Its IBM Vault® product is highlighted as a tool for identity protection and regulatory compliance, and IBM hosts webinars on trust, identity, and g…
  api_count: 1
  score_band: exemplar
  score_composite: 69.1
  shared: 3
- slug: nexgen-cloud
  name: NexGen Cloud
  description: NexGen Cloud Limited is a UK-headquartered AI cloud and GPU infrastructure provider. Its on-demand platform, Hyperstack, sells NVIDIA GPU and CPU virtual machines, managed Kubernetes clusters, block storage volumes, S3-compatible object st…
  api_count: 3
  score_band: strong
  score_composite: 65.9
  shared: 3
- slug: antimetal
  name: Antimetal
  description: Antimetal is a New York based software company building an autonomous production-management platform for engineering teams — "everything that happens after you deploy". It maintains a continuously updated world model of a customer's produc…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 3
- slug: terraform
  name: Terraform
  description: HashiCorp Terraform is an open-source infrastructure-as-code tool that enables teams to define, provision, and manage cloud infrastructure using a declarative configuration language (HCL). HCP Terraform and Terraform Enterprise expose a co…
  api_count: 2
  score_band: developing
  score_composite: 47.7
  shared: 3
- slug: cast-ai
  name: CAST AI
  description: CAST AI is an Application Performance Automation (APA) platform for Kubernetes that automates cost optimization, autoscaling, workload rightsizing, GPU/LLM workload placement, spot instance selection, and security posture analysis. The pla…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 3
- slug: oxide-computer
  name: Oxide
  description: 'Oxide Computer Company builds a rack-scale cloud computer: integrated server sleds (Gimlet), a rack-level switch (Sidecar), Oxide''s own illumos distribution (Helios), the Propolis/bhyve hypervisor and the Crucible distributed block store,…'
  api_count: 1
  score_band: developing
  score_composite: 46.1
  shared: 3
- slug: exoscale
  name: Exoscale
  description: Exoscale is a Swiss cloud infrastructure provider offering secure, reliable, and scalable cloud solutions to businesses of all sizes. Their services include virtual machines, object storage, networking, security, Kubernetes (SKS), Database…
  api_count: 1
  score_band: developing
  score_composite: 43.6
  shared: 3
- slug: hpe
  name: Hewlett Packard Enterprise
  description: Hewlett Packard Enterprise (HPE) is a global edge-to-cloud technology company providing servers, storage, networking, and hybrid cloud services, with HPE GreenLake serving as the unified edge-to-cloud platform delivering infrastructure as…
  api_count: 3
  score_band: developing
  score_composite: 41.2
  shared: 3
- slug: inspur-cloud
  name: Inspur Cloud
  description: Inspur Cloud (浪潮云) is the public-cloud arm of the Chinese IT conglomerate Inspur Group, operating from cloud.inspur.com across the cn-north-3 (华北三), cn-south-1 (华南一) and cn-east-1 (华东一) regions. It publishes a broad IaaS/PaaS catalog — 94…
  api_count: 18
  score_band: thin
  score_composite: 34.0
  shared: 3
- slug: kubeark
  name: Kubeark
  description: 'Kubeark is an enterprise orchestration and AI automation platform that standardizes system integration across hybrid estates. It combines three surfaces: workflow automation, where technical teams and end users build language-agnostic work…'
  api_count: 0
  score_band: thin
  score_composite: 32.7
  shared: 3
- slug: tensor9
  name: Tensor9
  description: Tensor9 is an enterprise BYOC (bring-your-own-cloud) / any-prem software deployment platform that lets software and AI vendors deploy their existing cloud-native stack into customer-owned environments — other public clouds, private VPCs, K…
  api_count: 0
  score_band: thin
  score_composite: 29.8
  shared: 3
- slug: nebius
  name: Nebius
  description: Nebius is an AI-focused cloud platform spun out of Yandex, offering NVIDIA GPU virtual machines and clusters (GB300, GB200, B300, B200, H200, H100) connected over InfiniBand, managed Kubernetes and Slurm (Soperator), S3-compatible storage,…
  api_count: 6
  score_band: emerging
  score_composite: 23.9
  shared: 3
- slug: tintri
  name: Tintri
  description: 'Tintri, now part of DDN, builds intelligent enterprise data-management and storage infrastructure: the VMstore virtualization-aware storage platform, the Tintri Cloud Platform (TCP) and Cloud Engine (TCE), and the Tintri Global Center (TGC…'
  api_count: 1
  score_band: emerging
  score_composite: 23.5
  shared: 3
- slug: diamanti
  name: Diamanti
  description: Diamanti was a San Jose, California infrastructure company (founded 2014) that built hyperconverged, bare-metal infrastructure purpose-built for containers and Kubernetes. Its flagship Ultima platform paired plug-and-play appliances with h…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 3
- slug: oracle-cloud
  name: Oracle Cloud Infrastructure
  description: Oracle Cloud Infrastructure (OCI) is Oracle's public cloud, exposed as a REST control plane of 159 service APIs covering compute, virtual cloud networking, block and object storage, identity and access management, Autonomous Database, Kube…
  api_count: 9
  score_band: exemplar
  score_composite: 76.4
  shared: 2
- slug: microsoft-azure-kubernetes-service
  name: Azure Kubernetes Service
  description: Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.
  api_count: 1
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: akuity
  name: Akuity
  description: 'Akuity is the enterprise software delivery company founded by the creators of Argo CD and Kargo. The Akuity Platform is its commercial, fully-managed offering: hosted, enterprise-grade Argo CD control planes for GitOps continuous delivery,…'
  api_count: 8
  score_band: exemplar
  score_composite: 72.9
  shared: 2
- slug: microsoft-azure-cdn
  name: Microsoft Azure Cdn
  description: Azure Content Delivery Network (CDN) caches static web content at strategically placed edge locations to deliver it to users with maximum throughput and minimum latency. The product is operated through the Microsoft.Cdn Azure Resource Mana…
  api_count: 2
  score_band: exemplar
  score_composite: 72.8
  shared: 2
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 3
  score_band: exemplar
  score_composite: 66.6
  shared: 2
- slug: calico
  name: Calico
  description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and secu…
  api_count: 1
  score_band: strong
  score_composite: 66.3
  shared: 2
- slug: red-hat-ansible-automation-platform
  name: Red Hat Ansible Automation Platform
  description: Red Hat Ansible Automation Platform is an enterprise automation solution that provides a framework for building and operating IT automation at scale. It includes the Automation Controller, Automation Hub, Event-Driven Ansible, and Ansible…
  api_count: 5
  score_band: strong
  score_composite: 66.0
  shared: 2
- slug: amazon-elastic-load-balancing
  name: Amazon Elastic Load Balancing
  description: Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for…
  api_count: 1
  score_band: strong
  score_composite: 65.8
  shared: 2
- slug: env0
  name: Env0
  description: env0 -- now trading as "env zero" -- is an infrastructure-as-code automation and cloud governance platform for Terraform, OpenTofu, Terragrunt, Pulumi, CloudFormation, Kubernetes and Helm. It provisions and manages cloud environments from…
  api_count: 1
  score_band: strong
  score_composite: 64.6
  shared: 2
- slug: modal-labs
  name: Modal
  description: Modal is a serverless cloud for AI, data, and general compute. Developers define infrastructure as code in Python (with JavaScript and Go SDKs) and run functions, GPUs, sandboxes, web endpoints, cron jobs, and volumes on demand. The primar…
  api_count: 1
  score_band: strong
  score_composite: 64.5
  shared: 2
- slug: microsoft-azure-private-link
  name: Microsoft Azure Private Link
  description: Microsoft Azure Private Link gives a virtual network a private IP address onto an Azure PaaS service, a partner service, or a service the customer publishes themselves, so traffic reaches it across the Microsoft backbone and never traverse…
  api_count: 2
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: koyeb
  name: Koyeb
  description: Koyeb is a developer-friendly serverless platform for deploying applications, Postgres databases, GPU workloads and isolated code-execution sandboxes across a global edge network. The Koyeb REST API is a Swagger 2.0 contract generated from…
  api_count: 1
  score_band: strong
  score_composite: 63.5
  shared: 2
---
