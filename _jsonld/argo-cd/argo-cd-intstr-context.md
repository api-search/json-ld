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
- intstrIntOrString
context_file: json-ld/argo-cd-intstr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-intstr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Intstr from Argo CD.
layout: jsonld
name: Argo Cd Intstr Context
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
  name: intVal
  type: integer
- container: ''
  name: strVal
  type: string
- container: ''
  name: type
  type: integer
property_count: 3
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-intstr-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"intstrIntOrString\": \"argocd:intstrIntOrString\",\n    \"intVal\": {\n      \"@id\": \"argocd:intVal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"strVal\": {\n      \"@id\": \"argocd:strVal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argocd:type\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-intstr-context.jsonld
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
