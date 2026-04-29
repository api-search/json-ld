---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
class_count: 10
classes:
- accountUpdatePasswordResponse
- accountUpdatePasswordRequest
- accountCreateTokenRequest
- accountAccountsList
- accountCreateTokenResponse
- accountToken
- accountAccount
- accountCanIResponse
- accountEmptyResponse
- name
context_file: json-ld/argo-cd-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Account from Argo CD.
layout: jsonld
name: Argo Cd Account Context
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
  name: currentPassword
  type: string
- container: ''
  name: newPassword
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: id
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: expiresAt
  type: integer
- container: ''
  name: issuedAt
  type: integer
- container: set
  name: capabilities
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: tokens
  type: string
- container: ''
  name: value
  type: string
property_count: 12
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-account-context
source_filename: argo-cd-account-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"accountUpdatePasswordResponse\": \"argocd:accountUpdatePasswordResponse\",\n    \"accountUpdatePasswordRequest\": \"argocd:accountUpdatePasswordRequest\",\n    \"accountCreateTokenRequest\": \"argocd:accountCreateTokenRequest\",\n    \"accountAccountsList\": \"argocd:accountAccountsList\",\n    \"accountCreateTokenResponse\": \"argocd:accountCreateTokenResponse\",\n    \"accountToken\": \"argocd:accountToken\",\n    \"accountAccount\": \"argocd:accountAccount\",\n    \"accountCanIResponse\": \"argocd:accountCanIResponse\",\n    \"accountEmptyResponse\": \"argocd:accountEmptyResponse\",\n    \"currentPassword\": {\n      \"@id\": \"argocd:currentPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\
  ,\n    \"newPassword\": {\n      \"@id\": \"argocd:newPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"argocd:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"argocd:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"argocd:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"argocd:expiresAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"issuedAt\": {\n      \"@id\": \"argocd:issuedAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"capabilities\": {\n      \"@id\": \"argocd:capabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"argocd:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tokens\": {\n      \"@id\": \"argocd:tokens\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-account-context.jsonld
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
