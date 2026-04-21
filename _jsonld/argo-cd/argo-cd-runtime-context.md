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
