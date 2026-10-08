---
layout: topic
slug: sunset-header
name: Sunset Header
kind: topic
description: The Sunset HTTP header field (RFC 8594) is an informational IETF specification that allows servers to communicate to clients that a URI is likely to become unresponsive at a specified future point in time. Published in May 2019, it provides a standardized mechanism for API deprecation signaling, enabling clients to plan migrations before service retirement. The header value is an HTTP-date timestamp following RFC 7231 syntax. A complementary sunset link relation type allows resources to reference documentation covering the sunset policy, migration guidance, and alternatives. RFC 9745 (Deprecation HTTP Header Field) extends this pattern by providing a two-phase deprecation + sunset lifecycle where Deprecation marks the start of deprecation and Sunset marks the end-of-life. These two headers are widely adopted in REST API governance practices and API lifecycle management tooling.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/sunset-header.png
tags:
- API Deprecation
- HTTP Headers
- RFC 8594
- RFC 9745
- API Lifecycle
- REST API
- Standards
repo: https://github.com/api-evangelist/sunset-header
api_count: 2
apis:
- name: Sunset Header (RFC 8594)
  description: The Sunset HTTP header field (RFC 8594) communicates the deprecation timeline of API endpoints to consumers. The header value is an HTTP-date timestamp indicating when a URI is expected to become unresponsive. It is accompanied by a sunset…
  url: https://datatracker.ietf.org/doc/html/rfc8594
- name: Deprecation HTTP Header Field (RFC 9745)
  description: RFC 9745 defines the Deprecation HTTP response header field, which signals to clients that a resource has been or will be deprecated. It complements the Sunset header by marking the start of the deprecation lifecycle. The header value is a…
  url: https://www.rfc-editor.org/rfc/rfc9745.html
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/sunset-header/blob/main/security/sunset-header-domain-security.yml
- type: Website
  url: https://datatracker.ietf.org/doc/html/rfc8594
- type: IETF Specification
  url: https://www.rfc-editor.org/rfc/rfc8594
provider_count: 0
providers: []
---
