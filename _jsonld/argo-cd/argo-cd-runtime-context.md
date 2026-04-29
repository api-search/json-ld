---
class_count: 3
classes:
- runtimeError
- runtimeStreamError
- runtimeRawExtension
context_file: json-ld/argo-cd-runtime-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-runtime-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Runtime from Argo CD.
layout: jsonld
name: Argo Cd Runtime Context
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
- container: ''
  name: raw
  type: string
property_count: 8
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-runtime-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"runtimeError\": \"argocd:runtimeError\",\n    \"runtimeStreamError\": \"argocd:runtimeStreamError\",\n    \"runtimeRawExtension\": \"argocd:runtimeRawExtension\",\n    \"code\": {\n      \"@id\": \"argocd:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"details\": {\n      \"@id\": \"argocd:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"argocd:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"argocd:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grpcCode\": {\n      \"@id\": \"argocd:grpc_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpCode\": {\n      \"@id\": \"argocd:http_code\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpStatus\": {\n      \"@id\": \"argocd:http_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"raw\": {\n      \"@id\": \"argocd:raw\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-runtime-context.jsonld
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
