---
layout: topic
slug: binary-format
name: Binary Format
kind: concept
description: Binary format refers to data encoding and serialization methods that use binary rather than text representations, including formats like Protocol Buffers, MessagePack, Avro, Thrift, CBOR, and others used in APIs and data storage systems for efficiency. Binary formats offer significant advantages over text-based formats in terms of size, parsing speed, and type safety.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/binary-format.png
tags:
- Binary Format
- Data Encoding
- Protocol Buffers
- Serialization
- MessagePack
- Apache Avro
- Apache Thrift
- CBOR
area: database
repo: https://github.com/api-evangelist/binary-format
api_count: 0
apis: []
links:
- type: Reference
  url: https://protobuf.dev
- type: Reference
  url: https://msgpack.org
- type: Reference
  url: https://avro.apache.org
- type: Reference
  url: https://thrift.apache.org
- type: Reference
  url: https://cbor.io
provider_count: 2
providers:
- slug: protocol-buffers
  name: Protocol Buffers
  description: Protocol Buffers (Protobuf) is Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data. It defines a schema language for specifying message structures in .proto files, which are compiled into effic…
  api_count: 1
  score_band: emerging
  score_composite: 24.5
  shared: 2
- slug: capn-proto
  name: Cap'n Proto
  description: Cap'n Proto is an open-source binary data interchange format and capability-based RPC protocol specification originally created by Kenton Varda. Unlike Protocol Buffers, Cap'n Proto's in-memory representation is identical to its wire forma…
  api_count: 5
  score_band: emerging
  score_composite: 12.6
  shared: 2
---
