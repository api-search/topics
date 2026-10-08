---
layout: topic
slug: write-ahead-log
name: Write Ahead Log
kind: topic
description: A Write-Ahead Log (WAL) is a standard technique in database systems where changes are first recorded to a sequential log file before being applied to the actual data files. It ensures durability and crash recovery by guaranteeing that committed transactions can be reconstructed from the log even if the system fails during a write operation.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/write-ahead-log.png
tags:
- Data Engineering
- Database
- Write Ahead Log
repo: https://github.com/api-evangelist/write-ahead-log
api_count: 0
apis: []
links: []
provider_count: 2
providers:
- slug: artie
  name: Artie
  description: Artie is a real-time data replication platform that streams database changes to cloud data warehouses and lakehouses with sub-minute latency and exactly-once delivery. It captures change data (CDC) from sources such as PostgreSQL, MySQL, M…
  api_count: 1
  score_band: developing
  score_composite: 47.9
  shared: 2
- slug: yunqi
  name: Yunqi (ClickZetta / Singdata Lakehouse)
  description: Yunqi (云器科技, English brands ClickZetta and Singdata) is a cloud-native AI Lakehouse company that unifies structured, semi-structured, and unstructured data on Apache Iceberg behind a single vectorized SQL engine. Its proprietary Generic In…
  api_count: 0
  score_band: thin
  score_composite: 31.9
  shared: 2
---
