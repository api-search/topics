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
  api_count: 39
  score_band: exemplar
  score_composite: 77.4
  shared: 3
- slug: localstack
  name: LocalStack
  description: LocalStack is a cloud service emulator that runs in a single container on your laptop or in your CI environment, providing a local test and mocking framework for developing cloud applications against AWS, Snowflake, and Azure without provi…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 3
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 25
  score_band: exemplar
  score_composite: 82.5
  shared: 2
- slug: amazon-dynamodb
  name: Amazon DynamoDB
  description: Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability, allowing you to store and retrieve any amount of data and serve any level of request traffic using key-valu…
  api_count: 19
  score_band: exemplar
  score_composite: 82.4
  shared: 2
- slug: amazon-efs
  name: Amazon EFS
  description: Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on demand to petabytes without disrupting applications, gro…
  api_count: 6
  score_band: exemplar
  score_composite: 77.1
  shared: 2
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 22
  score_band: exemplar
  score_composite: 76.4
  shared: 2
- slug: microsoft-azure-functions
  name: Microsoft Azure Functions
  description: Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmati…
  api_count: 1
  score_band: exemplar
  score_composite: 76.2
  shared: 2
- slug: amazon-eventbridge
  name: Amazon EventBridge
  description: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, SaaS applications, and AW…
  api_count: 12
  score_band: exemplar
  score_composite: 75.4
  shared: 2
- slug: amazon-redshift
  name: Amazon Redshift
  description: Amazon Redshift is a fast, fully managed cloud data warehouse from AWS that makes it simple and cost-effective to analyze all your data using standard SQL and existing BI tools. It exposes three APIs - the provisioned Redshift cluster API,…
  api_count: 35
  score_band: exemplar
  score_composite: 75.1
  shared: 2
- slug: aws-step-functions
  name: AWS Step Functions
  description: AWS Step Functions is a serverless orchestration service that lets you coordinate distributed applications and microservices using visual workflows, integrating with AWS services and supporting error handling and retries.
  api_count: 9
  score_band: exemplar
  score_composite: 74.5
  shared: 2
- slug: amazon-eventbridge-scheduler
  name: Amazon EventBridge Scheduler
  description: Amazon EventBridge Scheduler is a fully managed, serverless scheduler that enables you to create, run, and manage tasks from one central, managed service. With EventBridge Scheduler, you can create millions of schedules using cron and rate…
  api_count: 3
  score_band: exemplar
  score_composite: 73.3
  shared: 2
- slug: netlify
  name: Netlify
  description: Netlify is a cloud platform for building, deploying and scaling modern web applications, with continuous deployment from Git, serverless and edge functions, a global CDN, forms, identity, Postgres storage and an image CDN. Its public REST…
  api_count: 2
  score_band: exemplar
  score_composite: 72.2
  shared: 2
- slug: aws-app-runner
  name: AWS App Runner
  description: AWS App Runner is a fully managed service that makes it easy to build, deploy, and run containerized web applications and APIs at scale. It automatically builds and deploys applications from container images or source code, load balances t…
  api_count: 23
  score_band: exemplar
  score_composite: 71.9
  shared: 2
- slug: aws-glue
  name: AWS Glue
  description: AWS Glue is a fully managed serverless extract, transform, and load (ETL) service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development. It provides a central data catalog, c…
  api_count: 221
  score_band: exemplar
  score_composite: 71.7
  shared: 2
- slug: aws-elastic-beanstalk
  name: AWS Elastic Beanstalk
  description: AWS Elastic Beanstalk is a Platform-as-a-Service offering that makes it easy to deploy, scale, and manage web applications and services developed in Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar AWS infrastructure. It…
  api_count: 9
  score_band: exemplar
  score_composite: 71.2
  shared: 2
- slug: amazon-aurora-dsql
  name: Amazon Aurora DSQL
  description: Amazon Aurora DSQL is a distributed SQL database service optimized for transactional workloads. It provides a serverless, fully managed PostgreSQL-compatible database with built-in high availability, scalability, and global distribution ca…
  api_count: 4
  score_band: exemplar
  score_composite: 71.1
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 4
  score_band: exemplar
  score_composite: 70.5
  shared: 2
- slug: amazon-eventbridge-pipes
  name: Amazon EventBridge Pipes
  description: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of integration code you need to write and maintain when bu…
  api_count: 2
  score_band: exemplar
  score_composite: 70.3
  shared: 2
- slug: amazon-codecommit
  name: Amazon CodeCommit
  description: Amazon CodeCommit is a fully managed source control service that hosts secure Git repositories. It enables developers to store and version code in the AWS cloud, integrates with other AWS services, provides fine‑grained access control, and…
  api_count: 11
  score_band: exemplar
  score_composite: 69.9
  shared: 2
- slug: aws-waf
  name: AWS WAF
  description: AWS WAF is a web application firewall that monitors and controls HTTP and HTTPS requests forwarded to protected resources such as Amazon CloudFront distributions, API Gateway REST APIs, Application Load Balancers, AWS AppSync GraphQL APIs,…
  api_count: 18
  score_band: exemplar
  score_composite: 69.0
  shared: 2
- slug: amazon-web-services
  name: Amazon Web Services
  description: A network index of all Amazon Web Services (AWS) API profiles maintained by the API Evangelist organization, covering all AWS services across compute, storage, database, networking, security, AI/ML, and more.
  api_count: 377
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: amazon-appsync
  name: Amazon AppSync
  description: Amazon AppSync creates serverless GraphQL and Pub/Sub APIs that simplify application development through a single endpoint to securely query, update, or publish data.
  api_count: 14
  score_band: exemplar
  score_composite: 67.9
  shared: 2
- slug: amazon-well-architected-tool
  name: Amazon Well-Architected Tool
  description: The AWS Well-Architected Tool helps you review your workloads and compare them to the latest AWS architectural best practices. It provides a consistent process for evaluating architectures and implementing designs that scale over time acro…
  api_count: 22
  score_band: exemplar
  score_composite: 67.3
  shared: 2
- slug: aws-security-hub
  name: AWS Security Hub
  description: AWS Security Hub is a cloud security posture management (CSPM) service that aggregates, organizes, and prioritizes security findings from AWS services like Amazon GuardDuty, Inspector, and Macie, as well as supported third-party products.…
  api_count: 28
  score_band: exemplar
  score_composite: 66.5
  shared: 2
- slug: amazon-athena
  name: Amazon Athena
  description: Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.
  api_count: 15
  score_band: strong
  score_composite: 65.3
  shared: 2
- slug: amazon-serverless-application-repository
  name: Amazon Serverless Application Repository
  description: The AWS Serverless Application Repository enables teams, organizations, and individual developers to find, deploy, and publish serverless applications. It enables you to quickly deploy code samples, components, and complete applications fo…
  api_count: 5
  score_band: strong
  score_composite: 64.9
  shared: 2
- slug: amazon-fargate
  name: Amazon Fargate
  description: Amazon Fargate is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. Fargate removes the need to provision and manage servers, letting you specify and pay for resources per application, and improves…
  api_count: 6
  score_band: strong
  score_composite: 63.7
  shared: 2
- slug: azure-container-instances
  name: Azure Container Instances
  description: Azure Container Instances (ACI) is the fastest and simplest way to run containers in Azure without having to manage virtual machines or adopt a higher-level orchestration service. It offers serverless containers with per-second billing, cu…
  api_count: 2
  score_band: strong
  score_composite: 63.0
  shared: 2
- slug: amazon-migration-hub
  name: Amazon Migration Hub
  description: AWS Migration Hub provides a single location to track the progress of application migrations across multiple AWS and partner solutions, giving visibility into migration progress and enabling the use of other AWS migration tools.
  api_count: 14
  score_band: strong
  score_composite: 62.2
  shared: 2
- slug: chroma
  name: Chroma
  description: Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal ret…
  api_count: 1
  score_band: strong
  score_composite: 59.2
  shared: 2
---
