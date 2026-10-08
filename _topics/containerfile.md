---
layout: topic
slug: containerfile
name: Containerfile
kind: topic
description: A Containerfile is a plain text file that contains instructions for building container images. It is fully compatible with Docker's Dockerfile format and is the default file name used by Buildah and Podman. Containerfile instructions describe a base image (FROM), the steps to assemble the image (RUN, COPY, ADD, ARG, ENV), and runtime defaults (CMD, ENTRYPOINT, EXPOSE, USER, WORKDIR, VOLUME). Modern build engines extend the format with cache, secret, and SSH mounts and with platform-aware multi-stage builds.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/containerfile.png
tags:
- BuildKit
- Buildah
- Containers
- DevOps
- Docker
- Dockerfile
- Image Build
- OCI
- Podman
- Standards
repo: https://github.com/api-evangelist/containerfile
api_count: 4
apis:
- name: Containerfile Reference
  description: The official Containerfile reference shipped with the containers/common project. Documents every Containerfile instruction, syntax, and the ways Containerfile differs from Dockerfile, including secret mounts and platform-aware ARGs.
  url: https://github.com/containers/common/blob/main/docs/Containerfile.5.md
- name: Dockerfile Reference
  description: The Dockerfile format reference maintained by Docker. Containerfile is a strict superset of Dockerfile, so the Dockerfile reference covers the same instruction set with Docker-specific extensions such as directives like syntax= and check=.
  url: https://docs.docker.com/reference/dockerfile/
- name: BuildKit Dockerfile Frontend
  description: Dockerfile and Containerfile parsing in modern Docker is performed by BuildKit's Dockerfile frontend, distributed as a container image (docker/dockerfile). The frontend version is selected via the `# syntax=` directive and adds new feature…
  url: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md
- name: OCI Image Specification
  description: The Open Container Initiative Image Specification defines the format of the image artifacts that Containerfile and Dockerfile builds produce. The spec covers manifests, configuration, layers, and indexes consumed by container runtimes such…
  url: https://github.com/opencontainers/image-spec
links:
- type: IssueTracker
  url: https://github.com/containers/common/issues
- type: Releases
  url: https://github.com/containers/common/releases
- type: SecurityPolicy
  url: https://github.com/containers/common/blob/main/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/containers/common/blob/main/CODE-OF-CONDUCT.md
- type: ContributionGuide
  url: https://github.com/containers/common/blob/main/.github/CONTRIBUTING.md
- type: License
  url: https://github.com/containers/common/blob/main/LICENSE
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/containerfile/blob/main/security/containerfile-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/containerfile/blob/main/security/containerfile-domain-security.yml
- type: Specification
  url: https://github.com/containers/common/blob/main/docs/Containerfile.5.md
- type: Documentation
  url: https://docs.docker.com/reference/dockerfile/
- type: Reference
  url: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md
- type: Reference
  url: https://opencontainers.org/
- type: GitHubOrganization
  url: https://github.com/containers
- type: GitHubRepository
  url: https://github.com/containers/buildah
provider_count: 55
providers:
- slug: dagger
  name: Dagger
  description: Dagger is an open-source programmable CI/CD engine that runs pipelines in containers using a unified, introspectable GraphQL API. Pipelines are written as code in the developer's preferred language (Go, Python, TypeScript, PHP, Java, .NET,…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 4
- slug: amazon-ecr
  name: Amazon ECR
  description: Amazon Elastic Container Registry (ECR) is a fully managed container registry that makes it easy to store, manage, share, and deploy container images and artifacts. ECR eliminates the need to operate your own container repositories or worr…
  api_count: 1
  score_band: strong
  score_composite: 58.4
  shared: 3
- slug: goharbor
  name: GoHarbor
  description: 'Harbor is an open source, CNCF-hosted registry that stores, signs and scans OCI artifacts, adding the policy and identity layer a plain container registry lacks: projects, RBAC and robot accounts, vulnerability scanning and SBOM generation…'
  api_count: 2
  score_band: strong
  score_composite: 58.0
  shared: 3
- slug: docker-hub
  name: Docker Hub
  description: Docker Hub is the world's largest container image registry, providing a cloud-based service for finding, storing, sharing, and managing container images. It offers public and private repositories, automated builds, webhooks, and integratio…
  api_count: 1
  score_band: developing
  score_composite: 43.6
  shared: 3
- slug: docker
  name: Docker
  description: Docker is a platform for developers and sysadmins to build, share, and run applications in containers, packaging code and dependencies together for consistent deployment across environments.
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 3
- slug: drone
  name: Drone
  description: Drone is an open-source, container-native continuous integration and continuous delivery platform that automates software build, testing, and deployment pipelines entirely through Docker containers. Acquired by Harness in 2021, Drone enabl…
  api_count: 1
  score_band: thin
  score_composite: 39.1
  shared: 3
- slug: podman
  name: Podman
  description: Podman is a daemonless, open-source container engine for developing, managing, and running OCI containers on Linux, supporting both rootful and rootless operation as a drop-in replacement for Docker. The Podman REST API exposes a Docker-co…
  api_count: 1
  score_band: thin
  score_composite: 35.6
  shared: 3
- slug: open-container-initiative
  name: Open Container Initiative
  description: The Open Container Initiative (OCI) is an open governance structure for creating open industry standards around container formats and runtimes, hosted under the Linux Foundation.
  api_count: 1
  score_band: emerging
  score_composite: 23.0
  shared: 3
- slug: kamal-deploy
  name: Kamal
  description: Kamal is an open-source deployment tool from 37signals (DHH / Basecamp) for deploying containerized web applications to any infrastructure — bare metal, cloud VMs, or a mix — with zero-downtime rolling restarts. Originally built for Rails…
  api_count: 2
  score_band: emerging
  score_composite: 19.2
  shared: 3
- slug: coasts
  name: Coasts
  description: Coasts (Containerized Hosts) is an open-source, MIT-licensed CLI tool that provides localhost service isolation and orchestration for git worktrees. It spawns multiple fully isolated development runtimes for the same project on a single ma…
  api_count: 0
  score_band: emerging
  score_composite: 18.8
  shared: 3
- slug: nixpacks
  name: Nixpacks
  description: Nixpacks is an open-source build tool that converts application source code into OCI-compliant Docker images by combining language-specific providers, Nix packages, and Buildkit. Originally created by Railway as the build system powering t…
  api_count: 5
  score_band: emerging
  score_composite: 13.3
  shared: 3
- slug: dokku
  name: Dokku
  description: Dokku is an open-source Docker-powered self-hosted Platform-as-a-Service that helps you build and manage the lifecycle of applications from initial push to scaling out. Often described as "the smallest PaaS implementation you've ever seen"…
  api_count: 0
  score_band: emerging
  score_composite: 11.5
  shared: 3
- slug: easypanel
  name: Easypanel
  description: Easypanel is a modern, self-hosted server control panel powered by Docker and Docker Swarm that simplifies application deployment, database provisioning, and server management through an intuitive web interface. Operators can deploy applic…
  api_count: 0
  score_band: minimal
  score_composite: 9.0
  shared: 3
- slug: dchq
  name: DCHQ
  description: DCHQ (Data Center HQ) was a cloud automation and Docker container management platform out of San Francisco, offering both a hosted PaaS (DCHQ.io) and self-hosted on-premise editions for modeling, deploying, and managing container-based app…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 3
- slug: distelli
  name: Distelli
  description: Distelli was a Seattle-based DevOps and application-deployment company founded in 2013 by Rahul Singh and backed by Andreessen Horowitz (a16z). It offered a SaaS platform and command-line tooling for building, deploying, and managing appli…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 3
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 3
  score_band: exemplar
  score_composite: 75.3
  shared: 2
- slug: microsoft-azure-kubernetes-service
  name: Azure Kubernetes Service
  description: Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance.
  api_count: 1
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: ibm
  name: IBM
  description: IBM offers solutions that protect identities and sensitive access for enterprise customers. Its IBM Vault® product is highlighted as a tool for identity protection and regulatory compliance, and IBM hosts webinars on trust, identity, and g…
  api_count: 1
  score_band: exemplar
  score_composite: 69.1
  shared: 2
- slug: jfrog-container-registry
  name: JFrog Container Registry
  description: JFrog Container Registry is a free, hybrid, and multi-cloud Docker registry and Helm chart repository for managing and distributing container images. It provides advanced access control, vulnerability scanning, and scales to support enterp…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: upsun
  name: Upsun
  description: Upsun is the cloud application platform from Platform.sh that automatically builds, deploys, and scales applications with git-driven workflows, preview environments per branch, managed services, and usage-based pricing. Its REST API at api…
  api_count: 1
  score_band: strong
  score_composite: 60.1
  shared: 2
- slug: amazon-ecs
  name: Amazon ECS
  description: Amazon Elastic Container Service (ECS) is a fully managed container orchestration service that makes it easy to deploy, manage, and scale containerized applications.
  api_count: 1
  score_band: strong
  score_composite: 58.4
  shared: 2
- slug: platform.sh
  name: Platform.sh
  description: Platform.sh is the container-based Platform-as-a-Service (PaaS) founded in 2010 and headquartered in Paris and San Francisco, best known for Git-driven deployments in which a single push plus a few YAML files provisions an entire cluster o…
  api_count: 3
  score_band: strong
  score_composite: 57.9
  shared: 2
- slug: portainer
  name: Portainer
  description: Portainer provides a centralized multi‑cluster management platform for Kubernetes, Docker, Swarm and Podman workloads. It offers enterprise identity and access features such as SSO, LDAP and OIDC, as well as GitOps deployment workflows and…
  api_count: 1
  score_band: developing
  score_composite: 54.1
  shared: 2
- slug: gameye
  name: Gameye
  description: Gameye is a managed game server orchestration platform for multiplayer game studios, founded in 2017 in Rotterdam (Gameye B.V.). It runs dedicated, containerized game servers across bare metal, cloud, and edge providers behind a single RES…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: azure-container-registry
  name: Azure Container Registry
  description: Azure Container Registry is a managed Docker registry service based on the open-source Docker Registry for storing and managing private container images and artifacts. It supports automated container image builds, geo-replication, and inte…
  api_count: 1
  score_band: developing
  score_composite: 50.9
  shared: 2
- slug: buildpacks
  name: Cloud Native Buildpacks
  description: Cloud Native Buildpacks (CNBs) transform application source code into OCI-compliant container images that can run on any cloud, without requiring Dockerfiles. Initiated by Pivotal and Heroku in January 2018, CNB joined the CNCF as a Sandbo…
  api_count: 1
  score_band: developing
  score_composite: 49.0
  shared: 2
- slug: coolify
  name: Coolify
  description: Coolify is an open-source, self-hostable Platform-as-a-Service alternative to Vercel, Heroku, Netlify, and Railway. It lets you deploy static sites, APIs, full-stack applications, databases, and 280+ one-click services to any SSH-accessibl…
  api_count: 1
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: cosign
  name: Cosign
  description: Cosign is the command-line client of the Sigstore project for signing, verifying, and storing container images, OCI artifacts, blobs, and in-toto attestations. Cosign supports keyless signing using OpenID Connect identity providers (Google…
  api_count: 3
  score_band: developing
  score_composite: 42.5
  shared: 2
- slug: woodpecker-ci
  name: Woodpecker CI
  description: 'Woodpecker CI is a free, open-source (Apache-2.0) continuous integration and delivery engine, forked from Drone and maintained by a community organization on GitHub. It is self-hosted: an operator runs a Woodpecker server plus one or more…'
  api_count: 1
  score_band: developing
  score_composite: 41.8
  shared: 2
- slug: google-cloud-container-registry
  name: Google Cloud Container Registry
  description: Google Cloud Container Registry is a private Docker image storage service on Google Cloud Platform. It provides secure, private Docker image storage with integration into Google Cloud CI/CD pipelines, vulnerability scanning, and access con…
  api_count: 1
  score_band: thin
  score_composite: 38.8
  shared: 2
---
