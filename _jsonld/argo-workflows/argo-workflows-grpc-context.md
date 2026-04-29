---
api_specs:
- filename: argo-workflows-openapi.json
  format: json
  label: Argo Workflows API
  slug: argo-workflows
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/openapi/argo-workflows-openapi.json
class_count: 2
classes:
- grpc.gateway.runtime.Error
- grpc.gateway.runtime.StreamError
context_file: json-ld/argo-workflows-grpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-grpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Grpc from Argo Workflows.
layout: jsonld
name: Argo Workflows Grpc Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: integer
- container: set
  name: details
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: grpcCode
  type: integer
- container: ''
  name: httpCode
  type: integer
- container: ''
  name: httpStatus
  type: string
property_count: 7
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-grpc-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argo\": \"https://argoproj.github.io/schema/argo-workflows/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"grpc.gateway.runtime.Error\": \"argo:grpc.gateway.runtime.Error\",\n    \"grpc.gateway.runtime.StreamError\": \"argo:grpc.gateway.runtime.StreamError\",\n    \"code\": {\n      \"@id\": \"argo:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"details\": {\n      \"@id\": \"argo:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"argo:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"argo:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grpcCode\": {\n      \"@id\": \"argo:grpc_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpCode\": {\n      \"@id\": \"argo:http_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpStatus\"\
  : {\n      \"@id\": \"argo:http_status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-grpc-context.jsonld
tags:
- CNCF
- Containers
- Data Processing
- Kubernetes
- Machine Learning
- Open Source
- Workflow Engine
- JSON-LD
- Linked Data
- Semantic Web
---
