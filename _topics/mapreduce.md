---
layout: topic
slug: mapreduce
name: MapReduce
kind: concept
description: MapReduce is a programming model and processing technique for computing large data sets in parallel across a distributed cluster. Originally developed by Google and popularized by Apache Hadoop, it splits data processing into map and reduce phases to enable scalable big data analytics.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/mapreduce.png
tags:
- Big Data
- Data Processing
- Distributed Computing
- Hadoop
- MapReduce
area: database
repo: https://github.com/api-evangelist/mapreduce
api_count: 0
apis: []
links: []
provider_count: 26
providers:
- slug: hadoop
  name: Apache Hadoop
  description: Apache Hadoop is an open-source framework for distributed storage and processing of large datasets across clusters of computers using simple programming models. It includes HDFS for distributed storage, YARN for resource management, and Ma…
  api_count: 1
  score_band: thin
  score_composite: 29.4
  shared: 4
- slug: amazon-emr
  name: Amazon EMR
  description: Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics frameworks such as Apache Spark, Apache Hive, Apache H…
  api_count: 1
  score_band: strong
  score_composite: 62.5
  shared: 3
- slug: google-cloud-dataproc
  name: Google Cloud Dataproc
  description: Google Cloud Dataproc is a fully managed and highly scalable service for running Apache Spark, Apache Hadoop, Apache Flink, Presto, and other open-source data processing frameworks. It enables batch processing, querying, streaming, and mac…
  api_count: 1
  score_band: strong
  score_composite: 54.3
  shared: 3
- slug: pyspark
  name: Apache PySpark
  description: Python API for Apache Spark - A unified analytics engine for large-scale data processing supporting batch processing, streaming, machine learning, and graph computing.
  api_count: 5
  score_band: emerging
  score_composite: 17.8
  shared: 3
- slug: spark
  name: Apache Spark
  description: Open-source unified analytics engine for large-scale data processing with built-in modules for streaming, SQL, machine learning and graph processing.
  api_count: 0
  score_band: minimal
  score_composite: 1.8
  shared: 3
- slug: cloudera
  name: Cloudera
  description: Cloudera is a hybrid data platform company offering the Cloudera Data Platform (CDP) for data engineering, data warehousing, machine learning, streaming, and operational data. The platform exposes multiple REST APIs including the CDP Publi…
  api_count: 38
  score_band: exemplar
  score_composite: 68.3
  shared: 2
- slug: google-cloud-dataflow
  name: Google Cloud Dataflow
  description: Google Cloud Dataflow is a fully managed service for executing Apache Beam pipelines for batch and streaming data processing. It provides a serverless, fast, and cost-effective way to process data at scale.
  api_count: 1
  score_band: strong
  score_composite: 64.1
  shared: 2
- slug: kinesis
  name: AWS Kinesis
  description: Amazon Kinesis is a family of fully managed AWS services for collecting, processing, and analyzing real-time streaming data. The family includes Kinesis Data Streams for scalable record ingestion, Amazon Data Firehose (formerly Kinesis Dat…
  api_count: 4
  score_band: developing
  score_composite: 49.3
  shared: 2
- slug: apache-hbase
  name: Apache HBase
  description: Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable. It provides random, real-time read/write access to big data and runs on top of Apache Hadoop HDFS, offering a REST API (Starga…
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: apache-spark
  name: Apache Spark
  description: Apache Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports general execution graphs. Spark offers a comprehensive suite of AP…
  api_count: 6
  score_band: thin
  score_composite: 38.0
  shared: 2
- slug: apache-oozie
  name: Apache Oozie
  description: Apache Oozie is a workflow scheduler system for managing Apache Hadoop jobs. It enables users to define workflows as directed acyclic graphs (DAGs) of actions including MapReduce, Pig, Hive, Sqoop, and custom Java/shell steps. Coordinator…
  api_count: 1
  score_band: thin
  score_composite: 34.4
  shared: 2
- slug: apache-hive
  name: Apache Hive
  description: Apache Hive is a data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. It provides a SQL-like interface called HiveQL for querying data stored in Hadoop, along wit…
  api_count: 1
  score_band: thin
  score_composite: 32.8
  shared: 2
- slug: apache-giraph
  name: Apache Giraph
  description: Apache Giraph is an iterative graph processing system built for high scalability on Apache Hadoop. It is modeled after Google's Pregel and provides a simple yet flexible Java API for graph algorithms at massive scale using the Bulk Synchro…
  api_count: 1
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: cask
  name: Cask
  description: Cask Data, Inc. was the enterprise big-data startup, backed by Andreessen Horowitz, that built and open-sourced CDAP — the Cask Data Application Platform — a framework for building and running data analytic applications and data pipelines…
  api_count: 12
  score_band: thin
  score_composite: 31.2
  shared: 2
- slug: apache-atlas
  name: Apache Atlas
  description: Apache Atlas is a scalable and extensible set of core foundational data governance services developed by the Apache Software Foundation. It enables enterprises to effectively meet their compliance requirements within Hadoop and allows inte…
  api_count: 6
  score_band: thin
  score_composite: 31.0
  shared: 2
- slug: apache-samza
  name: Apache Samza
  description: Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both stream and batch processing.
  api_count: 1
  score_band: thin
  score_composite: 27.2
  shared: 2
- slug: flink
  name: Apache Flink
  description: Apache Flink is an open-source framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It is designed to run in all common cluster environments and to perform computations at in-memory…
  api_count: 1
  score_band: emerging
  score_composite: 24.3
  shared: 2
- slug: cask-data
  name: Cask Data
  description: Cask Data was the developer-tools company (originally Continuuity) behind CDAP, the Cask Data Application Platform — a 100% open source, integrated framework for building and running batch and real-time data-analytics applications and self…
  api_count: 0
  score_band: emerging
  score_composite: 24.0
  shared: 2
- slug: apache-orc
  name: Apache ORC
  description: Apache ORC is a self-describing, type-aware columnar file format designed for Hadoop workloads. It provides high compression ratios and fast read performance for large-scale data processing with support for complex data types.
  api_count: 3
  score_band: emerging
  score_composite: 20.6
  shared: 2
- slug: apache-tez
  name: Apache Tez
  description: Apache Tez is an application framework that allows for complex directed-acyclic-graph (DAG) based processing of data built on Apache Hadoop YARN. It is designed as a successor to MapReduce for executing Hive and Pig queries, providing a fl…
  api_count: 2
  score_band: emerging
  score_composite: 19.9
  shared: 2
- slug: apache-pig
  name: Apache Pig
  description: Apache Pig is a platform for analyzing large data sets that provides a high-level language (Pig Latin) for expressing data analysis programs. It compiles Pig Latin programs into MapReduce/Tez jobs and runs them on Hadoop clusters.
  api_count: 2
  score_band: emerging
  score_composite: 19.5
  shared: 2
- slug: apache-sqoop
  name: Apache Sqoop
  description: Apache Sqoop is a command-line tool designed for efficiently transferring bulk data between Apache Hadoop and structured data stores such as relational databases. It supports parallel import and export of data, incremental loads, and direc…
  api_count: 1
  score_band: emerging
  score_composite: 16.4
  shared: 2
- slug: flarion
  name: Flarion
  description: Flarion is a data-processing acceleration company that speeds up distributed compute engines — Apache Spark, Hadoop, and Ray — without code or infrastructure changes. It ships an Arrow-native, DataFusion/Polars-based execution engine writt…
  api_count: 0
  score_band: emerging
  score_composite: 13.7
  shared: 2
- slug: dualbird
  name: Dualbird
  description: Dualbird is a data and AI infrastructure company building accelerated data processing systems that speed up Apache Spark and Amazon EMR workloads by 10x-30x at 50%-90% lower cost, without code changes or migration. Founded by Gilad Tal (CE…
  api_count: 0
  score_band: minimal
  score_composite: 10.3
  shared: 2
- slug: concord-systems
  name: Concord Systems
  description: Concord Systems was a Brooklyn, New York stream-processing company founded in December 2014 by Alexander Gallego and Emilio Del Tesoro, and backed by Bloomberg Beta. It built a high-performance distributed stream processing framework writt…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: platfora
  name: Platfora
  description: Platfora was a big-data analytics company founded in 2011 by Ben Werther that provided in-memory business intelligence and data visualization directly on top of Apache Hadoop, letting analysts run interactive queries, build "lenses," and s…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
---
