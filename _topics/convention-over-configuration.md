---
layout: topic
slug: convention-over-configuration
name: Convention Over Configuration
kind: topic
description: Convention over Configuration (CoC) is a software design principle that prefers sensible defaults and standard patterns over explicit, repetitive configuration. Frameworks that adopt CoC reduce the number of decisions a developer must make to start a new project while still allowing overrides for non-standard cases. CoC was popularized by Ruby on Rails but predates Rails, drawing on UI principles like the principle of least astonishment and conventions in JavaBeans, Maven, and other Java ecosystems. The principle continues to shape modern frameworks such as Spring Boot, Next.js, Astro, Phoenix, Ember, Hugo, and Remix.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/convention-over-configuration.png
tags:
- Conventions
- Design Principle
- Framework
- Software Design
repo: https://github.com/api-evangelist/convention-over-configuration
api_count: 5
apis:
- name: Ruby on Rails
  description: Ruby on Rails is the framework that popularized convention over configuration. By default, an ActiveRecord model named Sale maps to a sales table, controllers map to RESTful resources, and the directory layout under app/ implies wiring wit…
  url: https://rubyonrails.org/
- name: Spring Boot
  description: Spring Boot is the convention-over-configuration evolution of the Spring Framework. Auto-configuration detects classpath dependencies and wires beans automatically, starter dependencies bundle common stacks, and standard application.yml pr…
  url: https://spring.io/projects/spring-boot
- name: Apache Maven
  description: Apache Maven introduced a strict project layout (src/main/java, src/test/java, target/) and a convention-driven build lifecycle. A pom.xml that declares dependencies and a parent POM is enough for most Java projects to compile, test, packa…
  url: https://maven.apache.org/
- name: Next.js
  description: Next.js exemplifies convention over configuration in modern web frameworks. The pages and app directory conventions auto-generate routes, file-based layouts, error boundaries, loading UI, and API routes without explicit router configuratio…
  url: https://nextjs.org/
- name: Hugo Static Site Generator
  description: Hugo defines content, layouts, archetypes, and partials by directory convention. A content/posts directory yields a section with a list page and per-post pages without explicit routing configuration.
  url: https://gohugo.io/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/convention-over-configuration/blob/main/security/convention-over-configuration-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/convention-over-configuration/blob/main/security/convention-over-configuration-domain-security.yml
- type: Reference
  url: https://en.wikipedia.org/wiki/Convention_over_configuration
- type: Reference
  url: https://rubyonrails.org/doctrine
- type: Reference
  url: https://docs.spring.io/spring-boot/index.html
- type: Reference
  url: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html
- type: Reference
  url: https://nextjs.org/docs
provider_count: 0
providers: []
---
