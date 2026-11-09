---
layout: topic
slug: serverless-patterns
name: Serverless Patterns
kind: concept
description: A collection of serverless architectures and patterns for building applications on AWS, featuring ready-to-use templates and best practices for Lambda, API Gateway, EventBridge, and other serverless services. Cloud adoption of this technology supports flexibility, cost optimization, and rapid deployment.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/serverless-patterns.png
tags:
- Architecture
- Amazon Web Services
- Cloud
- Patterns
- Serverless
area: microservices
repo: https://github.com/api-evangelist/serverless-patterns
api_count: 0
apis: []
links:
- type: LlmsText
  url: https://serverlessland.com/llms.txt
provider_count: 55
providers:
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 76.0
  shared: 3
- slug: localstack
  name: LocalStack
  description: LocalStack is a cloud service emulator that runs in a single container on your laptop or in your CI environment, providing a local test and mocking framework for developing cloud applications against AWS, Snowflake, and Azure without provi…
  api_count: 1
  score_band: developing
  score_composite: 53.2
  shared: 3
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 25
  score_band: exemplar
  score_composite: 82.8
  shared: 2
- slug: amazon-dynamodb
  name: Amazon DynamoDB
  description: Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability, allowing you to store and retrieve any amount of data and serve any level of request traffic using key-valu…
  api_count: 1
  score_band: exemplar
  score_composite: 80.9
  shared: 2
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 3
  score_band: exemplar
  score_composite: 75.4
  shared: 2
- slug: netlify
  name: Netlify
  description: Netlify is a cloud platform for building, deploying and scaling modern web applications, with continuous deployment from Git, serverless and edge functions, a global CDN, forms, identity, Postgres storage and an image CDN. Its public REST…
  api_count: 2
  score_band: exemplar
  score_composite: 72.8
  shared: 2
- slug: microsoft-azure-functions
  name: Microsoft Azure Functions
  description: Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmati…
  api_count: 1
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: amazon-efs
  name: Amazon EFS
  description: Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on demand to petabytes without disrupting applications, gro…
  api_count: 1
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: amazon-eventbridge
  name: Amazon EventBridge
  description: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, SaaS applications, and AW…
  api_count: 1
  score_band: exemplar
  score_composite: 66.9
  shared: 2
- slug: amazon-eventbridge-pipes
  name: Amazon EventBridge Pipes
  description: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of integration code you need to write and maintain when bu…
  api_count: 1
  score_band: exemplar
  score_composite: 66.5
  shared: 2
- slug: amazon-eventbridge-scheduler
  name: Amazon EventBridge Scheduler
  description: Amazon EventBridge Scheduler is a fully managed, serverless scheduler that enables you to create, run, and manage tasks from one central, managed service. With EventBridge Scheduler, you can create millions of schedules using cron and rate…
  api_count: 1
  score_band: exemplar
  score_composite: 66.5
  shared: 2
- slug: amazon-redshift
  name: Amazon Redshift
  description: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
  api_count: 2
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: amazon-well-architected-tool
  name: Amazon Well-Architected Tool
  description: The AWS Well-Architected Tool helps you review your workloads and compare them to the latest AWS architectural best practices. It provides a consistent process for evaluating architectures and implementing designs that scale over time acro…
  api_count: 1
  score_band: strong
  score_composite: 61.7
  shared: 2
- slug: aws-app-runner
  name: AWS App Runner
  description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances t…
  api_count: 16
  score_band: strong
  score_composite: 61.6
  shared: 2
- slug: amazon-web-services
  name: Amazon Web Services
  description: A network index of all Amazon Web Services (AWS) API profiles maintained by the API Evangelist organization, covering all AWS services across compute, storage, database, networking, security, AI/ML, and more.
  api_count: 377
  score_band: strong
  score_composite: 60.5
  shared: 2
- slug: amazon-proton
  name: Amazon Proton
  description: AWS Proton is a managed service for platform engineers that helps them publish standardized container and serverless application templates to empower developers. It provides automated infrastructure provisioning and manages deployment pipe…
  api_count: 1
  score_band: strong
  score_composite: 60.1
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: chroma
  name: Chroma
  description: Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal ret…
  api_count: 1
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: agentuity
  name: Agentuity
  description: Agentuity is a full-stack cloud platform for building, deploying, and operating AI agents and the framework apps around them. Developers keep their existing framework (Next.js, Hono, React Router, SvelteKit, Nuxt, Astro, Vite React, TanSta…
  api_count: 1
  score_band: strong
  score_composite: 57.9
  shared: 2
- slug: aws-step-functions
  name: AWS Step Functions
  description: AWS Step Functions is a serverless orchestration service that lets you coordinate distributed applications and microservices using visual workflows, integrating with AWS services and supporting error handling and retries.
  api_count: 10
  score_band: strong
  score_composite: 56.9
  shared: 2
- slug: amazon-serverless-application-repository
  name: Amazon Serverless Application Repository
  description: The AWS Serverless Application Repository enables teams, organizations, and individual developers to find, deploy, and publish serverless applications. It enables you to quickly deploy code samples, components, and complete applications fo…
  api_count: 5
  score_band: strong
  score_composite: 56.5
  shared: 2
- slug: amazon-fargate
  name: Amazon Fargate
  description: Amazon Fargate is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. Fargate removes the need to provision and manage servers, letting you specify and pay for resources per application, and improves…
  api_count: 6
  score_band: strong
  score_composite: 55.4
  shared: 2
- slug: aws-waf
  name: AWS WAF
  description: AWS WAF is a web application firewall that monitors and controls HTTP and HTTPS requests forwarded to protected resources such as Amazon CloudFront distributions, API Gateway REST APIs, Application Load Balancers, AWS AppSync GraphQL APIs,…
  api_count: 4
  score_band: strong
  score_composite: 55.1
  shared: 2
- slug: aws-glue
  name: AWS Glue
  description: AWS Glue is a fully managed serverless extract, transform, and load (ETL) service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development. It provides a central data catalog, c…
  api_count: 203
  score_band: strong
  score_composite: 54.5
  shared: 2
- slug: danubedata-ro
  name: Danube Data
  description: DanubeData provides managed EU cloud infrastructure, offering virtual machines, managed databases, in‑memory caches, object storage and serverless containers to developers and businesses. The platform includes a CLI, Terraform and Pulumi p…
  api_count: 1
  score_band: developing
  score_composite: 54.2
  shared: 2
- slug: runpod
  name: RunPod
  description: RunPod is a managed GPU cloud and serverless inference platform offering on-demand and persistent GPU Pods, autoscaling Serverless endpoints, network volumes, container templates, and a REST + GraphQL control plane for provisioning H100, H…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 2
- slug: alphaus
  name: Alphaus
  description: Alphaus is a Tokyo-based cloud FinOps company (No. 1 in Japan) whose platform helps enterprises, managed service providers, and cloud resellers manage and optimize multi-cloud spend across AWS, Azure, and GCP. Its products include Octo (co…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: amazon-migration-hub
  name: Amazon Migration Hub
  description: AWS Migration Hub provides a single location to track the progress of application migrations across multiple AWS and partner solutions, giving visibility into migration progress and enabling the use of other AWS migration tools.
  api_count: 1
  score_band: developing
  score_composite: 52.9
  shared: 2
- slug: azure-container-instances
  name: Azure Container Instances
  description: Azure Container Instances (ACI) is the fastest and simplest way to run containers in Azure without having to manage virtual machines or adopt a higher-level orchestration service. It offers serverless containers with per-second billing, cu…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 2
- slug: vast-ai
  name: Vast.ai
  description: Vast.ai is a decentralized GPU marketplace that matches buyers with 40+ datacenters and individual hosts renting out NVIDIA GPUs at market prices. It exposes a REST API, Python SDK, and vastai CLI for searching GPU offers, renting instance…
  api_count: 1
  score_band: developing
  score_composite: 52.2
  shared: 2
---
