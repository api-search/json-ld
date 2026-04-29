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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"projectSyncWindowsResponse\": \"argocd:projectSyncWindowsResponse\",\n    \"projectGlobalProjectsResponse\": \"argocd:projectGlobalProjectsResponse\",\n    \"projectProjectTokenResponse\": \"argocd:projectProjectTokenResponse\",\n    \"projectEmptyResponse\": \"argocd:projectEmptyResponse\",\n    \"projectDetailedProjectsResponse\": \"argocd:projectDetailedProjectsResponse\",\n    \"projectProjectUpdateRequest\": \"argocd:projectProjectUpdateRequest\",\n    \"projectProjectCreateRequest\": \"argocd:projectProjectCreateRequest\",\n    \"projectProjectTokenCreateRequest\": \"argocd:projectProjectTokenCreateRequest\",\n    \"windows\": {\n      \"@id\": \"argocd:windows\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"argocd:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusters\": {\n      \"@id\": \"argocd:clusters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"globalProjects\": {\n      \"@id\": \"argocd:globalProjects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"argocd:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"argocd:repositories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upsert\": {\n      \"@id\": \"argocd:upsert\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": \"schema:description\",\n    \"expiresIn\": {\n      \"@id\": \"argocd:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"id\": {\n      \"@id\": \"argocd:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"argocd:role\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-project-context.jsonld
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
