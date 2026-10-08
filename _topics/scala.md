---
layout: topic
slug: scala
name: Scala
kind: topic
description: A topic collection covering the Scala programming language ecosystem, including its standard library, key frameworks, and widely-used libraries. Scala is a strongly-typed, JVM-based language that blends object-oriented and functional programming, widely used in big data engineering, distributed systems, fintech, and backend development. The ecosystem includes the Akka actor framework, Play web framework, ZIO effect system, Cats typeclass library, http4s, Slick, sbt build tool, and Spark. Scala 3.8 is the current major version (January 2026).
image: https://www.scala-lang.org/resources/img/scala-logo.png
tags:
- Big Data
- Distributed Systems
- Functional Programming
- JVM
- Programming Language
- Scala
- Scala 3
- Type Safety
repo: https://github.com/api-evangelist/scala
api_count: 11
apis:
- name: Scala Standard Library API
  description: The Scala Standard Library provides core data structures, collections, concurrent primitives, and runtime utilities for Scala programs on the JVM, JavaScript (Scala.js), and Native (Scala Native) runtimes. Scala 3.8 shipped in January 2026…
  url: https://www.scala-lang.org/api/current/
- name: Akka API
  description: Akka is a toolkit for building highly concurrent, distributed, and fault-tolerant applications on the JVM using the Actor model. Includes Akka Actors, Akka HTTP, Akka Streams, and Akka Cluster.
  url: https://doc.akka.io/
- name: Akka HTTP API
  description: Akka HTTP provides a full server- and client-side HTTP stack built on Akka Streams. Offers high-throughput, non-blocking HTTP handling with a powerful Scala DSL for routing and marshalling.
  url: https://doc.akka.io/docs/akka-http/current/
- name: Play Framework API
  description: Play is a reactive web framework for Scala (and Java) built on Akka and Akka Streams. Provides MVC routing, template engine, WS client, and reactive database integrations for building web applications and REST APIs.
  url: https://www.playframework.com/
- name: ZIO API
  description: ZIO is a type-safe, composable library for asynchronous and concurrent programming in Scala. Provides a purely functional effect system with structured concurrency, resource management, and a rich ecosystem of ZIO-based libraries (ZIO HTTP…
  url: https://zio.dev/
- name: Cats API
  description: Cats is a lightweight, modular library for functional programming in Scala. It provides type class abstractions (Functor, Monad, Applicative, etc.) and their instances for standard library types. The most widely used functional programming…
  url: https://typelevel.org/cats/
- name: http4s API
  description: http4s is a typeful, functional, streaming HTTP library for Scala built on cats-effect and fs2. Provides server and client abstractions with backends for Blaze, Ember, Jetty, and Tomcat. Second most popular HTTP library in the Scala ecosys…
  url: https://http4s.org/
- name: Slick API
  description: Slick is Functional Relational Mapping (FRM) for Scala — a type-safe, composable database access library that lets you work with stored data almost as if you were using Scala collections. Supports PostgreSQL, MySQL, H2, SQLite, and more.
  url: https://scala-slick.org/
- name: Circe API
  description: Circe is the most widely used JSON library for Scala, built on top of Cats. Provides encoding, decoding, traversal, and transformation of JSON values with automatic derivation support for case classes and sealed traits.
  url: https://circe.github.io/circe/
- name: Apache Spark API
  description: Apache Spark is the dominant big data processing framework in the Scala ecosystem. Its API enables large-scale data processing, SQL analytics, streaming, and machine learning across distributed clusters.
  url: https://spark.apache.org/docs/latest/api/scala/
- name: sbt Build Tool
  description: sbt (Simple Build Tool) is the dominant build tool in the Scala ecosystem (90% adoption). Its Server API enables IDE integration via the Build Server Protocol (BSP). sbt 2.0 release candidates show up to 41% faster startup.
  url: https://www.scala-sbt.org/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/scala/blob/main/security/scala-domain-security.yml
- type: Website
  url: https://www.scala-lang.org/
- type: Blog
  url: https://www.scala-lang.org/blog/
- type: Documentation
  url: https://docs.scala-lang.org/
- type: Forums
  url: https://users.scala-lang.org/
- type: GitHub
  url: https://github.com/scala
- type: Newsletter
  url: https://scalatimes.com/
- type: Social
  url: https://twitter.com/scala_lang
- type: Community
  url: https://discord.gg/scala
- type: JSONSchema
  url: https://github.com/api-evangelist/scala/blob/main/json-schema/scala-library-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/scala/blob/main/json-structure/scala-library-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/scala/blob/main/json-ld/scala-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/scala/blob/main/vocabulary/scala-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/scala/blob/main/examples/scala-zio-http-example.json
- type: Examples
  url: https://github.com/api-evangelist/scala/blob/main/examples/scala-cats-effect-http4s-example.json
provider_count: 9
providers:
- slug: unison-computing
  name: Unison Computing
  description: Unison Computing, PBC is a public benefit corporation building the Unison programming language, Unison Cloud, and Unison Share. Unison is a statically-typed functional language where code is content-addressed and immutable; Unison Cloud de…
  api_count: 1
  score_band: thin
  score_composite: 31.9
  shared: 3
- slug: lightbend
  name: Lightbend
  description: Lightbend, Inc. (dba Akka) is the company behind the Akka agentic systems platform. Founded as Typesafe by the creators of the Scala language and the Akka actor toolkit, the company built the JVM reactive stack — Akka actors, Akka Streams,…
  api_count: 0
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of librari…
  api_count: 1
  score_band: thin
  score_composite: 32.9
  shared: 2
- slug: vineyard
  name: Vineyard
  description: Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyar…
  api_count: 1
  score_band: thin
  score_composite: 29.7
  shared: 2
- slug: redplanetlabs
  name: Redplanetlabs
  description: Red Planet Labs builds Rama, a unified backend platform for the JVM (Java/Clojure) that consolidates databases, queues, workers, and infrastructure into a single programming model — aiming to reduce backend complexity by up to 100x while p…
  api_count: 1
  score_band: emerging
  score_composite: 25.6
  shared: 2
- slug: groovy
  name: Apache Groovy
  description: Apache Groovy is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at improving developer productivity thanks to a concise, familiar and easy to learn syn…
  api_count: 3
  score_band: emerging
  score_composite: 16.3
  shared: 2
- slug: java
  name: Java
  description: Java is a high-level, class-based, object-oriented programming language developed by Sun Microsystems and now stewarded by Oracle. The Java Standard Edition (SE) platform provides a comprehensive set of APIs and class libraries for buildin…
  api_count: 9
  score_band: emerging
  score_composite: 16.3
  shared: 2
- slug: kotlin
  name: Kotlin
  description: Kotlin is a modern, concise, and safe programming language for the JVM, Android, and multiplatform development. It is developed by JetBrains and provides full interoperability with Java. Kotlin's standard library and ecosystem offer rich A…
  api_count: 2
  score_band: emerging
  score_composite: 14.0
  shared: 2
- slug: concord-systems
  name: Concord Systems
  description: Concord Systems was a Brooklyn, New York stream-processing company founded in December 2014 by Alexander Gallego and Emilio Del Tesoro, and backed by Bloomberg Beta. It built a high-performance distributed stream processing framework writt…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
