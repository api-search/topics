---
layout: topic
slug: mlops
name: MLOps
kind: concept
description: MLOps (Machine Learning Operations) is an engineering discipline that unifies machine learning development with operations to deploy, monitor, govern, and maintain machine learning models in production. MLOps.org publishes an end-to-end reference for designing, building, and managing reproducible, testable, and evolvable ML-powered software, including the CRISP-ML(Q) process model, the MLOps Stack Canvas, MLOps principles, and ML model governance practices. This index curates the canonical references, frameworks, and ecosystem resources for practicing MLOps across data engineering, ML pipelines, and model serving.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/mlops.png
tags:
- AI Operations
- CRISP-ML(Q)
- DevOps
- Machine Learning
- ML Engineering
- ML Governance
- ML Pipelines
- Model Deployment
- Model Monitoring
- Model Serving
area: machine-learning
repo: https://github.com/api-evangelist/mlops
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/mlops/blob/main/security/mlops-domain-security.yml
- type: Website
  url: https://ml-ops.org/
- type: Motivation
  url: https://ml-ops.org/content/motivation
- type: Designing ML Software
  url: https://ml-ops.org/content/phase-zero
- type: ML Workflow Lifecycle
  url: https://ml-ops.org/content/end-to-end-ml-workflow
- type: Three Levels of ML Software
  url: https://ml-ops.org/content/three-levels-of-ml-software
- type: MLOps Principles
  url: https://ml-ops.org/content/mlops-principles
- type: CRISP-ML(Q)
  url: https://ml-ops.org/content/crisp-ml
- type: MLOps Stack Canvas
  url: https://ml-ops.org/content/mlops-stack-canvas
- type: ML Model Governance
  url: https://ml-ops.org/content/model-governance
- type: References
  url: https://ml-ops.org/content/references
- type: State of MLOps
  url: https://ml-ops.org/content/state-of-mlops
- type: Publisher
  url: https://www.innoq.com/
- type: License
  url: https://creativecommons.org/licenses/by/4.0/
- type: JSONLD
  url: https://github.com/api-evangelist/mlops/blob/main/json-ld/mlops-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/mlops/blob/main/json-schema/mlops-model-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/mlops/blob/main/json-schema/mlops-pipeline-schema.json
provider_count: 44
providers:
- slug: seldon
  name: Seldon
  description: Seldon is a Kubernetes-native MLOps platform that enables enterprises to deploy, monitor, manage, and explain machine learning models at scale. The platform provides REST and gRPC inference APIs that follow the Open Inference Protocol, ena…
  api_count: 3
  score_band: thin
  score_composite: 32.0
  shared: 3
- slug: striveworks
  name: Striveworks
  description: Striveworks is an Austin, Texas enterprise AI operations (AIOps) company whose platform, Chariot, lets organizations build, deploy, monitor and continuously retrain machine-learning models — in hours rather than months — across cloud, on-p…
  api_count: 1
  score_band: emerging
  score_composite: 25.6
  shared: 3
- slug: qwak
  name: Qwak
  description: Qwak is an end-to-end production machine learning platform that lets data science and ML engineering teams build, train, deploy, monitor, and manage models with minimal engineering friction. The platform unifies MLOps, LLMOps, and a Featur…
  api_count: 0
  score_band: emerging
  score_composite: 21.3
  shared: 3
- slug: amazon-codeguru-profiler
  name: Amazon CodeGuru Profiler
  description: Amazon CodeGuru Profiler collects runtime performance data from your live applications, providing recommendations to help you reduce CPU utilization, cut costs, and improve application performance. The profiler analyzes your application's…
  api_count: 1
  score_band: exemplar
  score_composite: 77.3
  shared: 2
- slug: edge-impulse
  name: Edge Impulse
  description: Edge Impulse is the end-to-end edge AI MLOps platform for building datasets, training and optimizing machine learning models, and deploying them directly on device — from the smallest microcontrollers to gateways with the latest neural acc…
  api_count: 2
  score_band: exemplar
  score_composite: 71.5
  shared: 2
- slug: comet
  name: Comet
  description: Comet is an enterprise AI/ML developer platform used by over 150,000 developers and organizations including Netflix, Uber, and Autodesk. Its flagship open-source product, Opik, is an LLM observability, evaluation, and optimization suite fo…
  api_count: 1
  score_band: strong
  score_composite: 65.3
  shared: 2
- slug: ibm
  name: IBM
  description: IBM offers solutions that protect identities and sensitive access for enterprise customers. Its IBM Vault® product is highlighted as a tool for identity protection and regulatory compliance, and IBM hosts webinars on trust, identity, and g…
  api_count: 1
  score_band: strong
  score_composite: 64.9
  shared: 2
- slug: rightnow
  name: RightNow AI
  description: RightNow AI (RunInfra) turns plain-English descriptions of an inference workload into production, OpenAI-compatible AI endpoints. The platform selects open-source models from Hugging Face, benchmarks GPU options, applies kernel optimizatio…
  api_count: 1
  score_band: strong
  score_composite: 62.7
  shared: 2
- slug: amazon-devops-guru
  name: Amazon DevOps Guru
  description: Amazon DevOps Guru is a machine learning-powered service that makes it easy to improve an application's operational performance and availability. It detects behaviors that deviate from normal operating patterns so you can identify operatio…
  api_count: 1
  score_band: strong
  score_composite: 60.9
  shared: 2
- slug: simplismart
  name: Simplismart
  description: Simplismart is an AI inference and model-deployment platform that lets teams run, fine-tune, and self-host generative AI models on optimized GPU infrastructure. It offers OpenAI-compatible LLM chat inference (Llama, Qwen, Gemma, Mixtral, D…
  api_count: 18
  score_band: strong
  score_composite: 60.2
  shared: 2
- slug: h2o-ai
  name: H2O.ai
  description: H2O.ai is an open-source artificial-intelligence and machine-learning company whose platform spans H2O-3 (a distributed, in-memory ML engine), H2O Driverless AI (automatic machine learning), H2O MLOps (model deployment, scoring and monitor…
  api_count: 2
  score_band: strong
  score_composite: 57.8
  shared: 2
- slug: replicate
  name: Replicate
  description: Replicate lets you run machine learning models in the cloud with a simple API. Thousands of open-source models are available, and you can run your own custom models at scale. Run image generation, language models, audio synthesis, video ge…
  api_count: 1
  score_band: strong
  score_composite: 57.5
  shared: 2
- slug: databricks
  name: Databricks
  description: Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.
  api_count: 1
  score_band: strong
  score_composite: 57.1
  shared: 2
- slug: inference
  name: Inference
  description: Inference (inference.net) is an AI infrastructure platform for AI-native teams. It offers an OpenAI-compatible inference API for open-source, frontier, and custom fine-tuned language models, alongside Catalyst — its observability, tracing,…
  api_count: 1
  score_band: strong
  score_composite: 55.9
  shared: 2
- slug: fiddlerai
  name: fiddler.ai
  description: Fiddler AI is an enterprise AI Observability and Security platform — an "AI Control Plane" for AI agents, LLM applications, and traditional ML models. It delivers unified monitoring, real-time guardrails (safety, hallucination/faithfulness…
  api_count: 1
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: microsoft-azure-machine-learning
  name: Azure Machine Learning
  description: Azure Machine Learning is an enterprise-grade cloud service for building, training, deploying, and managing machine learning models. It supports the full ML lifecycle including data preparation, model training, evaluation, deployment, and…
  api_count: 2
  score_band: strong
  score_composite: 54.5
  shared: 2
- slug: oxen
  name: Oxen
  description: Oxen.ai is a blazing-fast data version control system and AI platform for teams building with their own data. Its open-source Rust core (liboxen) versions, branches, and shares terabyte-scale datasets, model weights, and experiments withou…
  api_count: 2
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: amazon-bedrock
  name: Amazon Bedrock
  description: Amazon Bedrock is a fully managed AWS service that makes high-performing foundation models from leading AI companies available through a unified API for building generative AI applications. It supports text and image generation, conversati…
  api_count: 2
  score_band: developing
  score_composite: 51.4
  shared: 2
- slug: amazon-codeguru-reviewer
  name: Amazon CodeGuru Reviewer
  description: Amazon CodeGuru Reviewer is an automated code review service that uses machine learning and AWS best practices to identify security vulnerabilities, bugs, and hard-to-detect issues in your Java and Python code. It provides intelligent reco…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: launchable
  name: Launchable
  description: Launchable is a software development intelligence platform for continuous integration that applies machine learning to CI and test data to speed up software delivery. Its flagship capability, Predictive Test Selection, records builds, test…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: furiosa
  name: FuriosaAI
  description: FuriosaAI is a South Korean semiconductor company that designs data-center AI inference chips and the software stack that runs on them. Its second-generation NPU, RNGD, implements a Tensor Contraction Processor architecture on TSMC 5nm and…
  api_count: 2
  score_band: developing
  score_composite: 45.0
  shared: 2
- slug: triton
  name: Triton Inference Server
  description: NVIDIA Triton Inference Server provides a cloud and edge inferencing solution optimized for both CPUs and GPUs. Triton supports an HTTP/REST and gRPC protocol that allows remote clients to request inferencing for any model being managed by…
  api_count: 2
  score_band: thin
  score_composite: 36.7
  shared: 2
- slug: tensorflow
  name: TensorFlow
  description: TensorFlow is an end-to-end open source machine learning platform developed by Google. It provides a comprehensive ecosystem of tools, libraries, and community resources for building and deploying ML-powered applications, including model t…
  api_count: 1
  score_band: thin
  score_composite: 35.1
  shared: 2
- slug: modelop
  name: ModelOp
  description: ModelOp is enterprise software for governing and operationalizing artificial intelligence at scale. Founded as Open Data Group and headquartered in Chicago, Illinois, it sells an "AI system of record" — the Enterprise AI Command Center, po…
  api_count: 1
  score_band: thin
  score_composite: 33.9
  shared: 2
- slug: scalable-inference-serving
  name: Scalable Inference Serving
  description: A collection of APIs, frameworks, and platforms for scalable machine learning model inference serving, deployment, and management. This includes the KServe Open Inference Protocol (the CNCF standard for model serving on Kubernetes), BentoM…
  api_count: 1
  score_band: thin
  score_composite: 33.8
  shared: 2
- slug: bentoml
  name: BentoML
  description: BentoML is an open-source unified inference platform for building, packaging, and deploying machine learning models as scalable REST API services. Developers define services using Python class decorators that automatically expose model inf…
  api_count: 1
  score_band: thin
  score_composite: 33.7
  shared: 2
- slug: kubeflow
  name: Kubeflow
  description: Kubeflow is an open-source machine learning platform for Kubernetes, designed to make deployments of ML workflows on Kubernetes simple, portable, and scalable. It provides tools for training, serving, tuning, and managing ML models across…
  api_count: 1
  score_band: thin
  score_composite: 33.0
  shared: 2
- slug: domino-data-lab
  name: Domino Data Lab
  description: Domino Data Lab is an enterprise MLOps and AI platform used by data science and machine learning teams to build, deploy, monitor, and govern models and data-science applications across hybrid and multi-cloud infrastructure. The platform ex…
  api_count: 1
  score_band: thin
  score_composite: 32.7
  shared: 2
- slug: ray
  name: Ray
  description: Ray is an open-source unified compute framework, stewarded by Anyscale, that scales Python and AI workloads from a laptop to a cluster. It consists of Ray Core (a distributed runtime) and a set of AI libraries (Ray Train, Ray Data, Ray Tun…
  api_count: 1
  score_band: thin
  score_composite: 31.3
  shared: 2
- slug: google-tensorflow
  name: Google TensorFlow
  description: Google TensorFlow is an open-source machine learning framework providing APIs and tools for building, training, and deploying ML models, including TensorFlow Serving for model inference and TensorFlow Hub for reusable model components.
  api_count: 1
  score_band: thin
  score_composite: 30.7
  shared: 2
---
