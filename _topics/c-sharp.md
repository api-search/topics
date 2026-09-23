---
layout: topic
slug: c-sharp
name: C#
kind: topic
description: C# is a modern, object-oriented programming language developed by Microsoft as part of the .NET platform. It is used for building Windows applications, web services, games (via Unity), and enterprise software, offering strong typing, garbage collection, and rich framework support. The C# language is defined by a standardized specification and implemented by the Roslyn compiler, with packages distributed via NuGet and running on the .NET runtime.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/c-sharp.png
tags:
- .NET
- C#
- Microsoft
- Programming Language
- Topic
- Roslyn
- NuGet
- Dotnet
- Language
repo: https://github.com/api-evangelist/c-sharp
api_count: 5
apis:
- name: C# Language
  description: 'The C# language itself: syntax, semantics, type system, and standard library conventions. Maintained by Microsoft with a formal ECMA-334 specification and modern features such as records, pattern matching, async/await, and nullable referen…'
  url: https://learn.microsoft.com/en-us/dotnet/csharp/
- name: Roslyn (.NET Compiler Platform)
  description: Roslyn is the open-source .NET compiler platform that provides C# and Visual Basic compilers with rich code analysis APIs, enabling custom analyzers, refactorings, and tooling.
  url: https://github.com/dotnet/roslyn
- name: .NET Runtime
  description: The .NET runtime hosts and executes C# programs, providing the CLR, base class libraries, garbage collection, and cross-platform support for Windows, Linux, and macOS.
  url: https://github.com/dotnet/runtime
- name: NuGet Package Manager
  description: NuGet is the package manager for .NET, providing a central registry of open-source and commercial libraries distributed as packages for use in C# and other .NET projects. NuGet exposes a documented HTTP API for package discovery and publis…
  url: https://www.nuget.org
- name: ASP.NET Core
  description: ASP.NET Core is the cross-platform web framework for C#, used to build web applications, APIs, and real-time services on the .NET runtime.
  url: https://learn.microsoft.com/en-us/aspnet/core
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/c-sharp/blob/main/security/c-sharp-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/c-sharp/blob/main/security/c-sharp-domain-security.yml
- type: Website
  url: https://learn.microsoft.com/en-us/dotnet/csharp/
- type: Documentation
  url: https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/
- type: Language Reference
  url: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/
- type: Specification
  url: https://learn.microsoft.com/en-us/dotnet/csharp/specification/
- type: GitHubOrg
  url: https://github.com/dotnet
- type: Roslyn Compiler
  url: https://github.com/dotnet/roslyn
- type: .NET Runtime
  url: https://github.com/dotnet/runtime
- type: .NET Docs
  url: https://github.com/dotnet/docs
- type: NuGet
  url: https://www.nuget.org
- type: Download .NET
  url: https://dotnet.microsoft.com/download
- type: Blog
  url: https://devblogs.microsoft.com/dotnet/
- type: Community
  url: https://dotnet.microsoft.com/platform/community
provider_count: 9
providers:
- slug: microsoft-net
  name: Microsoft .NET
  description: Microsoft .NET is a free, cross-platform, open source developer platform for building many different types of applications. The .NET APIs and developer tools provide programmatic access to .NET runtime services, NuGet package management, p…
  api_count: 10
  score_band: strong
  score_composite: 60.9
  shared: 3
- slug: restsharp
  name: RestSharp
  description: RestSharp is a simple REST and HTTP API client library for .NET that wraps HttpClient with a fluent API for making HTTP requests with automatic serialization and deserialization of request and response bodies. Supports JSON, XML, and CSV f…
  api_count: 1
  score_band: emerging
  score_composite: 21.6
  shared: 3
- slug: refitter
  name: Refitter
  description: Refitter is a .NET tool and source generator that produces Refit HTTP client interfaces from OpenAPI specifications. It runs at compile time as a source generator or as a standalone CLI tool (dotnet-refitter), enabling type-safe API consum…
  api_count: 2
  score_band: thin
  score_composite: 34.1
  shared: 2
- slug: microsoft-package
  name: Microsoft Package
  description: A collection of Microsoft package management APIs covering NuGet, Windows Package Manager (WinGet), Microsoft Store, and Azure Artifacts for managing and distributing software packages across Microsoft platforms.
  api_count: 8
  score_band: thin
  score_composite: 33.4
  shared: 2
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from A…'
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: polly
  name: Polly
  description: Polly is a .NET resilience and transient-fault-handling library that allows developers to express resilience strategies such as Retry, Circuit Breaker, Hedging, Timeout, Rate Limiter, and Fallback in a fluent and thread-safe manner. A .NET…
  api_count: 1
  score_band: emerging
  score_composite: 17.9
  shared: 2
- slug: nunit
  name: NUnit
  description: NUnit is a unit-testing framework for all .NET languages. Initially ported from JUnit, the current production release has been completely rewritten with many new features and support for a wide range of .NET platforms. NUnit is a software…
  api_count: 4
  score_band: emerging
  score_composite: 15.3
  shared: 2
- slug: xamarin
  name: Xamarin
  description: Xamarin was the San Francisco company behind the Mono-based cross-platform mobile development framework, letting developers build native iOS, Android, and Mac apps from a single C#/.NET codebase. Backed by investors including Insight Partn…
  api_count: 0
  score_band: emerging
  score_composite: 13.9
  shared: 2
- slug: aptera
  name: Aptera
  description: Aptera (Aptera Software, Inc.) was a custom software development consultancy based in Fort Wayne, Indiana, founded in 2003 and specializing in the Microsoft stack — .NET, SharePoint, Azure, business intelligence, and web and mobile applica…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 2
---
