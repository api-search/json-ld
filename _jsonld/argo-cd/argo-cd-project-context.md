---
class_count: 9
classes:
- projectSyncWindowsResponse
- projectGlobalProjectsResponse
- projectProjectTokenResponse
- projectEmptyResponse
- projectDetailedProjectsResponse
- projectProjectUpdateRequest
- projectProjectCreateRequest
- projectProjectTokenCreateRequest
- description
context_file: json-ld/argo-cd-project-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-project-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Project from Argo CD.
layout: jsonld
name: Argo Cd Project Context
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
  name: windows
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: token
  type: string
- container: set
  name: clusters
  type: string
- container: set
  name: globalProjects
  type: string
- container: ''
  name: project
  type: string
- container: set
  name: repositories
  type: string
- container: ''
  name: upsert
  type: boolean
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: role
  type: string
property_count: 11
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-project-context
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
