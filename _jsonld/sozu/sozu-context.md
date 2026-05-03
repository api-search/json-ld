---
class_count: 8
classes:
- ReverseProxy
- Cluster
- Backend
- Frontend
- Listener
- Certificate
- Worker
- ProxyConfiguration
context_file: json-ld/sozu-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-ld/sozu-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sozu from Sozu.
layout: jsonld
name: Sozu Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sozu
  uri: https://api-evangelist.github.io/sozu/vocab#
properties:
- container: ''
  name: clusterId
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: backendId
  type: string
- container: ''
  name: backendHost
  type: string
- container: ''
  name: backendPort
  type: integer
- container: ''
  name: frontendId
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: pathPrefix
  type: string
- container: ''
  name: listenAddress
  type: string
- container: ''
  name: listenPort
  type: integer
- container: ''
  name: protocol
  type: string
- container: ''
  name: certificateDomain
  type: string
- container: ''
  name: certificateExpiry
  type: dateTime
- container: ''
  name: workerPid
  type: integer
- container: ''
  name: workerStatus
  type: string
- container: ''
  name: connectionCount
  type: integer
property_count: 16
provider_name: Sozu
provider_slug: sozu
slug: sozu-context
source_filename: sozu-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sozu\": \"https://api-evangelist.github.io/sozu/vocab#\",\n\n    \"ReverseProxy\": \"schema:SoftwareApplication\",\n    \"Cluster\": \"sozu:Cluster\",\n    \"Backend\": \"sozu:Backend\",\n    \"Frontend\": \"sozu:Frontend\",\n    \"Listener\": \"sozu:Listener\",\n    \"Certificate\": \"schema:DigitalDocument\",\n    \"Worker\": \"sozu:Worker\",\n    \"ProxyConfiguration\": \"schema:StructuredValue\",\n\n    \"clusterId\": {\n      \"@id\": \"sozu:clusterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backendId\": {\n      \"@id\": \"sozu:backendId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backendHost\": {\n      \"@id\": \"sozu:backendHost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backendPort\": {\n      \"@id\"\
  : \"sozu:backendPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"frontendId\": {\n      \"@id\": \"sozu:frontendId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathPrefix\": {\n      \"@id\": \"sozu:pathPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listenAddress\": {\n      \"@id\": \"sozu:listenAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listenPort\": {\n      \"@id\": \"sozu:listenPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocol\": {\n      \"@id\": \"sozu:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateDomain\": {\n      \"@id\": \"sozu:certificateDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateExpiry\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"workerPid\": {\n      \"@id\": \"sozu:workerPid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  workerStatus\": {\n      \"@id\": \"sozu:workerStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionCount\": {\n      \"@id\": \"sozu:connectionCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sozu/refs/heads/main/json-ld/sozu-context.jsonld
tags:
- Proxy
- Reverse Proxy
- Load Balancing
- Rust
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
