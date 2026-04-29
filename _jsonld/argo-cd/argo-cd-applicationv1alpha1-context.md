---
class_count: 4
classes:
- applicationv1alpha1ResourceStatus
- applicationv1alpha1EnvEntry
- name
- version
context_file: json-ld/argo-cd-applicationv1alpha1-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-applicationv1alpha1-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Applicationv1Alpha1 from Argo CD.
layout: jsonld
name: Argo Cd Applicationv1Alpha1 Context
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
  name: group
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: hook
  type: boolean
- container: ''
  name: kind
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: requiresDeletionConfirmation
  type: boolean
- container: ''
  name: requiresPruning
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: syncWave
  type: integer
- container: ''
  name: value
  type: string
property_count: 10
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-applicationv1alpha1-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"applicationv1alpha1ResourceStatus\": \"argocd:applicationv1alpha1ResourceStatus\",\n    \"applicationv1alpha1EnvEntry\": \"argocd:applicationv1alpha1EnvEntry\",\n    \"group\": {\n      \"@id\": \"argocd:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"argocd:health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hook\": {\n      \"@id\": \"argocd:hook\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kind\": {\n      \"@id\": \"argocd:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"namespace\": {\n      \"@id\": \"argocd:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiresDeletionConfirmation\": {\n      \"@id\": \"argocd:requiresDeletionConfirmation\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requiresPruning\": {\n      \"@id\": \"argocd:requiresPruning\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"argocd:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncWave\": {\n      \"@id\": \"argocd:syncWave\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": \"schema:version\",\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-applicationv1alpha1-context.jsonld
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
