---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
class_count: 1
classes:
- protobufAny
context_file: json-ld/argo-cd-protobuf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-protobuf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Protobuf from Argo CD.
layout: jsonld
name: Argo Cd Protobuf Context
namespaces:
- prefix: argocd
  uri: https://argoproj.github.io/schema/argo-cd/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
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
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-protobuf-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"protobufAny\": \"argocd:protobufAny\",\n    \"typeUrl\": {\n      \"@id\": \"argocd:type_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-protobuf-context.jsonld
tags:
- Continuous Delivery
- Containers
- Deployment
- GitOps
- Kubernetes
- CNCF
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
