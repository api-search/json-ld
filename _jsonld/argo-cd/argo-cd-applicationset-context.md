---
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
