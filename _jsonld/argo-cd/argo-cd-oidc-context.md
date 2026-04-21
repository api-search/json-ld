---
class_count: 1
classes:
- oidcClaim
context_file: json-ld/argo-cd-oidc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-oidc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Oidc from Argo CD.
layout: jsonld
name: Argo Cd Oidc Context
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
  name: essential
  type: boolean
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: string
property_count: 3
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-oidc-context
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
