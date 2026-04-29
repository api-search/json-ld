---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
class_count: 3
classes:
- applicationsetApplicationSetResponse
- applicationsetApplicationSetGenerateRequest
- applicationsetApplicationSetGenerateResponse
context_file: json-ld/argo-cd-applicationset-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-applicationset-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Applicationset from Argo CD.
layout: jsonld
name: Argo Cd Applicationset Context
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
  name: applicationset
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: applicationSet
  type: string
- container: set
  name: applications
  type: string
property_count: 4
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-applicationset-context
source_filename: argo-cd-applicationset-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"applicationsetApplicationSetResponse\": \"argocd:applicationsetApplicationSetResponse\",\n    \"applicationsetApplicationSetGenerateRequest\": \"argocd:applicationsetApplicationSetGenerateRequest\",\n    \"applicationsetApplicationSetGenerateResponse\": \"argocd:applicationsetApplicationSetGenerateResponse\",\n    \"applicationset\": {\n      \"@id\": \"argocd:applicationset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"argocd:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationSet\": {\n      \"@id\": \"argocd:applicationSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications\": {\n      \"@id\": \"argocd:applications\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-applicationset-context.jsonld
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
