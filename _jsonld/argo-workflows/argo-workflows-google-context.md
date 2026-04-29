---
api_specs:
- filename: argo-workflows-openapi.json
  format: json
  label: Argo Workflows API
  slug: argo-workflows
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/openapi/argo-workflows-openapi.json
class_count: 1
classes:
- google.protobuf.Any
context_file: json-ld/argo-workflows-google-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-google-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Google from Argo Workflows.
layout: jsonld
name: Argo Workflows Google Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: typeUrl
  type: string
- container: ''
  name: value
  type: string
property_count: 2
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-google-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argo\": \"https://argoproj.github.io/schema/argo-workflows/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"google.protobuf.Any\": \"argo:google.protobuf.Any\",\n    \"typeUrl\": {\n      \"@id\": \"argo:type_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"argo:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-google-context.jsonld
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
