---
class_count: 2
classes:
- gpgkeyGnuPGPublicKeyResponse
- gpgkeyGnuPGPublicKeyCreateResponse
context_file: json-ld/argo-cd-gpgkey-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-gpgkey-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Gpgkey from Argo CD.
layout: jsonld
name: Argo Cd Gpgkey Context
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
  name: created
  type: string
- container: set
  name: skipped
  type: string
property_count: 2
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-gpgkey-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gpgkeyGnuPGPublicKeyResponse\": \"argocd:gpgkeyGnuPGPublicKeyResponse\",\n    \"gpgkeyGnuPGPublicKeyCreateResponse\": \"argocd:gpgkeyGnuPGPublicKeyCreateResponse\",\n    \"created\": {\n      \"@id\": \"argocd:created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skipped\": {\n      \"@id\": \"argocd:skipped\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-gpgkey-context.jsonld
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
