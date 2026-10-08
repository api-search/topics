---
layout: topic
slug: jcr
name: JCR
kind: topic
description: JCR (Java Content Repository) is a Java specification (JSR-283, "Content Repository for Java Technology API 2.0") that provides a vendor-neutral, implementation-independent way to access content bi-directionally on a granular level within a content repository. It defines features for hierarchical content modeling, versioning, access control, search, locking, and observation, with the javax.jcr package as its core. The reference implementation is provided by the Apache Jackrabbit project.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jcr.png
tags:
- CMS
- Content Repository
- Java
- JCR
- JSR-283
- Standards
repo: https://github.com/api-evangelist/jcr
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/jcr/blob/main/security/jcr-domain-security.yml
- type: Website
  url: https://jcp.org/en/jsr/detail?id=283
- type: ReferenceImplementation
  url: https://jackrabbit.apache.org
- type: Specification
  url: http://jcp.org/aboutJava/communityprocess/final/jsr283/index.html
provider_count: 4
providers:
- slug: dotcms
  name: dotCMS
  description: dotCMS is a Java-based visual headless content management system aimed at compliance-led enterprises, deployable as SaaS (dotCMS Cloud), on premise, or as a managed service. It covers content modelling, authoring, workflow, multi-site mana…
  api_count: 1
  score_band: exemplar
  score_composite: 71.9
  shared: 2
- slug: eclipse
  name: Eclipse Foundation
  description: The Eclipse Foundation is a non-profit (Belgian AISBL) that provides a global community of individuals and organizations with a mature, scalable and business-friendly environment for open source software collaboration and innovation. It is…
  api_count: 19
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: apache-sling
  name: Apache Sling
  description: Apache Sling is a RESTful web framework built on top of the Java Content Repository (JCR) standard. It maps HTTP requests to content resources using a resource-oriented URL decomposition model and uses scripts or servlets to render respons…
  api_count: 3
  score_band: emerging
  score_composite: 22.9
  shared: 2
- slug: jakarta-ee
  name: Jakarta EE
  description: Jakarta EE is the open source successor to Java EE, providing a set of specifications for enterprise Java development. Jakarta EE is developed under the Eclipse Foundation and includes specifications for web services, messaging, persistenc…
  api_count: 6
  score_band: emerging
  score_composite: 13.4
  shared: 2
---
