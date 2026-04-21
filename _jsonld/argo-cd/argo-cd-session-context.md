---
class_count: 3
classes:
- sessionGetUserInfoResponse
- sessionSessionCreateRequest
- sessionSessionResponse
context_file: json-ld/argo-cd-session-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-session-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Session from Argo CD.
layout: jsonld
name: Argo Cd Session Context
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
- container: set
  name: groups
  type: string
- container: ''
  name: iss
  type: string
- container: ''
  name: loggedIn
  type: boolean
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: token
  type: string
property_count: 6
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-session-context
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
