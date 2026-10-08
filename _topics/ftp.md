---
layout: topic
slug: ftp
name: FTP
kind: topic
description: FTP (File Transfer Protocol) is a standard network protocol used to transfer files between a client and a server over a TCP-based network. FTP is a protocol specification rather than a vendor or HTTP API, and is documented primarily in IETF standards (RFC 959 and follow-ups) and in widely deployed server implementations such as vsftpd, ProFTPD, Pure-FTPd, and FileZilla Server. This index links to the canonical specifications and documentation for the protocol; no OpenAPI is generated because FTP is not an HTTP API.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ftp.png
tags:
- FTP
- File Transfer
- Network Protocol
- IETF
- Standards
repo: https://github.com/api-evangelist/ftp
api_count: 0
apis: []
links:
- type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc959
- type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc2228
- type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc2428
- type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc4217
- type: Documentation
  url: https://en.wikipedia.org/wiki/File_Transfer_Protocol
- type: Documentation
  url: https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml
- type: Implementation
  url: https://security.appspot.com/vsftpd.html
- type: Implementation
  url: http://www.proftpd.org/
- type: Implementation
  url: https://www.pureftpd.org/
- type: Implementation
  url: https://filezilla-project.org/
provider_count: 1
providers:
- slug: amazon-transfer-family
  name: Amazon Transfer Family
  description: AWS Transfer Family is a secure transfer service that enables you to transfer files into and out of AWS storage services. It supports SFTP, FTPS, and FTP protocols, providing a fully managed file transfer service with native integration to…
  api_count: 71
  score_band: developing
  score_composite: 50.3
  shared: 2
---
