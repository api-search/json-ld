---
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
