---
class_count: 7
classes:
- VertxConfiguration
- VerticleDeployment
- HealthCheckResponse
- EventBusConfig
- ClusterConfig
- HttpServerConfig
- HealthCheckResult
context_file: json-ld/vert-x-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-ld/vert-x-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vert X from Vert.x.
layout: jsonld
name: Vert X Context
namespaces:
- prefix: vertx
  uri: https://vertx.io/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: eclipse
  uri: https://www.eclipse.org/vocabulary/
properties:
- container: ''
  name: http
  type: reference
- container: ''
  name: eventBus
  type: reference
- container: ''
  name: cluster
  type: reference
- container: ''
  name: port
  type: integer
- container: ''
  name: host
  type: string
- container: ''
  name: ssl
  type: boolean
- container: ''
  name: keyStorePath
  type: string
- container: ''
  name: keyStorePassword
  type: string
- container: ''
  name: compressionSupported
  type: boolean
- container: ''
  name: idleTimeout
  type: integer
- container: ''
  name: maxWebSocketFrameSize
  type: integer
- container: ''
  name: clusterPublicHost
  type: string
- container: ''
  name: clusterPublicPort
  type: integer
- container: ''
  name: clusterPingInterval
  type: integer
- container: ''
  name: clusterPingReplyInterval
  type: integer
- container: ''
  name: connectTimeout
  type: integer
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: clusterManager
  type: string
- container: ''
  name: workerPoolSize
  type: integer
- container: ''
  name: eventLoopPoolSize
  type: integer
- container: ''
  name: internalBlockingPoolSize
  type: integer
- container: ''
  name: haEnabled
  type: boolean
- container: ''
  name: haGroup
  type: string
- container: ''
  name: quorumSize
  type: integer
- container: ''
  name: blockedThreadCheckInterval
  type: integer
- container: ''
  name: maxEventLoopExecuteTime
  type: long
- container: ''
  name: maxWorkerExecuteTime
  type: long
- container: ''
  name: warningExceptionTime
  type: long
- container: ''
  name: main
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: instances
  type: integer
- container: ''
  name: worker
  type: boolean
- container: ''
  name: multiThreaded
  type: boolean
- container: ''
  name: ha
  type: boolean
- container: ''
  name: isolationGroup
  type: string
- container: list
  name: isolatedClasses
  type: ''
- container: list
  name: extraClasspath
  type: ''
- container: ''
  name: config
  type: reference
- container: ''
  name: workerPoolName
  type: string
- container: ''
  name: status
  type: string
- container: list
  name: checks
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: data
  type: reference
- container: ''
  name: outcome
  type: string
property_count: 44
provider_name: Vert.x
provider_slug: vert-x
slug: vert-x-context
source_filename: vert-x-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vertx\": \"https://vertx.io/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"eclipse\": \"https://www.eclipse.org/vocabulary/\",\n\n    \"VertxConfiguration\": \"vertx:VertxConfiguration\",\n    \"VerticleDeployment\": \"vertx:VerticleDeployment\",\n    \"HealthCheckResponse\": \"vertx:HealthCheckResponse\",\n    \"EventBusConfig\": \"vertx:EventBusConfig\",\n    \"ClusterConfig\": \"vertx:ClusterConfig\",\n    \"HttpServerConfig\": \"vertx:HttpServerConfig\",\n    \"HealthCheckResult\": \"vertx:HealthCheckResult\",\n\n    \"http\": {\n      \"@id\": \"vertx:httpConfig\",\n      \"@type\": \"@id\"\n    },\n    \"eventBus\": {\n      \"@id\": \"vertx:eventBusConfig\",\n      \"@type\": \"@id\"\n    },\n    \"cluster\": {\n      \"@id\": \"vertx:clusterConfig\",\n      \"@type\": \"@id\"\n    },\n    \"port\": {\n      \"@id\": \"vertx:port\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"host\": {\n      \"@id\": \"vertx:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssl\": {\n      \"@id\": \"vertx:ssl\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"keyStorePath\": {\n      \"@id\": \"vertx:keyStorePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyStorePassword\": {\n      \"@id\": \"vertx:keyStorePassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compressionSupported\": {\n      \"@id\": \"vertx:compressionSupported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"idleTimeout\": {\n      \"@id\": \"vertx:idleTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxWebSocketFrameSize\": {\n      \"@id\": \"vertx:maxWebSocketFrameSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clusterPublicHost\": {\n      \"@id\": \"vertx:clusterPublicHost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterPublicPort\": {\n      \"@id\": \"vertx:clusterPublicPort\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"clusterPingInterval\": {\n      \"@id\": \"vertx:clusterPingInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clusterPingReplyInterval\": {\n      \"@id\": \"vertx:clusterPingReplyInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"connectTimeout\": {\n      \"@id\": \"vertx:connectTimeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"vertx:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"clusterManager\": {\n      \"@id\": \"vertx:clusterManager\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerPoolSize\": {\n      \"@id\": \"vertx:workerPoolSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventLoopPoolSize\": {\n      \"@id\": \"vertx:eventLoopPoolSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"internalBlockingPoolSize\": {\n      \"@id\": \"vertx:internalBlockingPoolSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"haEnabled\": {\n      \"@id\": \"vertx:haEnabled\",\n \
  \     \"@type\": \"xsd:boolean\"\n    },\n    \"haGroup\": {\n      \"@id\": \"vertx:haGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quorumSize\": {\n      \"@id\": \"vertx:quorumSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blockedThreadCheckInterval\": {\n      \"@id\": \"vertx:blockedThreadCheckInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxEventLoopExecuteTime\": {\n      \"@id\": \"vertx:maxEventLoopExecuteTime\",\n      \"@type\": \"xsd:long\"\n    },\n    \"maxWorkerExecuteTime\": {\n      \"@id\": \"vertx:maxWorkerExecuteTime\",\n      \"@type\": \"xsd:long\"\n    },\n    \"warningExceptionTime\": {\n      \"@id\": \"vertx:warningExceptionTime\",\n      \"@type\": \"xsd:long\"\n    },\n    \"main\": {\n      \"@id\": \"vertx:mainVerticle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"vertx:deploymentOptions\",\n      \"@type\": \"@id\"\n    },\n    \"instances\": {\n      \"@id\": \"vertx:instances\",\n \
  \     \"@type\": \"xsd:integer\"\n    },\n    \"worker\": {\n      \"@id\": \"vertx:worker\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"multiThreaded\": {\n      \"@id\": \"vertx:multiThreaded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ha\": {\n      \"@id\": \"vertx:ha\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isolationGroup\": {\n      \"@id\": \"vertx:isolationGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isolatedClasses\": {\n      \"@id\": \"vertx:isolatedClasses\",\n      \"@container\": \"@list\"\n    },\n    \"extraClasspath\": {\n      \"@id\": \"vertx:extraClasspath\",\n      \"@container\": \"@list\"\n    },\n    \"config\": {\n      \"@id\": \"vertx:verticleConfig\",\n      \"@type\": \"@id\"\n    },\n    \"workerPoolName\": {\n      \"@id\": \"vertx:workerPoolName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checks\": {\n      \"@id\": \"\
  vertx:healthChecks\",\n      \"@container\": \"@list\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"vertx:checkData\",\n      \"@type\": \"@id\"\n    },\n    \"outcome\": {\n      \"@id\": \"vertx:outcome\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vert-x/refs/heads/main/json-ld/vert-x-context.jsonld
tags:
- Event-Driven
- Frameworks
- Java
- JVM
- Microservices
- Polyglot
- Reactive
- Eclipse Foundation
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
