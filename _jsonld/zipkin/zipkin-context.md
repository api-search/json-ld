---
api_specs:
- filename: zipkin-api-v2.yml
  format: yaml
  label: Zipkin API V2
  slug: zipkin-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/openapi/zipkin-api-v2.yml
class_count: 4
classes:
- Span
- Endpoint
- Annotation
- DependencyLink
context_file: json-ld/zipkin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/json-ld/zipkin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zipkin from Zipkin.
layout: jsonld
name: Zipkin Context
namespaces:
- prefix: zipkin
  uri: https://zipkin.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: traceId
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: timestamp
  type: long
- container: ''
  name: duration
  type: long
- container: ''
  name: localEndpoint
  type: reference
- container: ''
  name: remoteEndpoint
  type: reference
- container: list
  name: annotations
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: serviceName
  type: string
- container: ''
  name: ipv4
  type: string
- container: ''
  name: ipv6
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: value
  type: string
- container: ''
  name: parent
  type: string
- container: ''
  name: child
  type: string
- container: ''
  name: callCount
  type: integer
- container: ''
  name: errorCount
  type: integer
property_count: 20
provider_name: Zipkin
provider_slug: zipkin
slug: zipkin-context
source_filename: zipkin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zipkin\": \"https://zipkin.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Span\": \"zipkin:Span\",\n    \"Endpoint\": \"zipkin:Endpoint\",\n    \"Annotation\": \"zipkin:Annotation\",\n    \"DependencyLink\": \"zipkin:DependencyLink\",\n    \"traceId\": {\"@id\": \"zipkin:traceId\", \"@type\": \"xsd:string\"},\n    \"parentId\": {\"@id\": \"zipkin:parentId\", \"@type\": \"xsd:string\"},\n    \"id\": {\"@id\": \"zipkin:id\", \"@type\": \"xsd:string\"},\n    \"kind\": {\"@id\": \"zipkin:kind\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"zipkin:name\", \"@type\": \"xsd:string\"},\n    \"timestamp\": {\"@id\": \"zipkin:timestamp\", \"@type\": \"xsd:long\"},\n    \"duration\": {\"@id\": \"zipkin:duration\", \"@type\": \"xsd:long\"},\n    \"localEndpoint\": {\"@id\": \"zipkin:localEndpoint\", \"@type\": \"@id\"},\n    \"remoteEndpoint\": {\"@id\": \"\
  zipkin:remoteEndpoint\", \"@type\": \"@id\"},\n    \"annotations\": {\"@id\": \"zipkin:annotations\", \"@container\": \"@list\"},\n    \"tags\": {\"@id\": \"zipkin:tags\"},\n    \"serviceName\": {\"@id\": \"zipkin:serviceName\", \"@type\": \"xsd:string\"},\n    \"ipv4\": {\"@id\": \"zipkin:ipv4\", \"@type\": \"xsd:string\"},\n    \"ipv6\": {\"@id\": \"zipkin:ipv6\", \"@type\": \"xsd:string\"},\n    \"port\": {\"@id\": \"zipkin:port\", \"@type\": \"xsd:integer\"},\n    \"value\": {\"@id\": \"zipkin:value\", \"@type\": \"xsd:string\"},\n    \"parent\": {\"@id\": \"zipkin:parent\", \"@type\": \"xsd:string\"},\n    \"child\": {\"@id\": \"zipkin:child\", \"@type\": \"xsd:string\"},\n    \"callCount\": {\"@id\": \"zipkin:callCount\", \"@type\": \"xsd:integer\"},\n    \"errorCount\": {\"@id\": \"zipkin:errorCount\", \"@type\": \"xsd:integer\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zipkin/refs/heads/main/json-ld/zipkin-context.jsonld
tags:
- Distributed Tracing
- Observability
- Open Source
- Microservices
- JSON-LD
- Linked Data
- Semantic Web
---
