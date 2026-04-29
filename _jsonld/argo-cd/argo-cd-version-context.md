---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
class_count: 1
classes:
- versionVersionMessage
context_file: json-ld/argo-cd-version-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-version-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd Version from Argo CD.
layout: jsonld
name: Argo Cd Version Context
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
  name: BuildDate
  type: string
- container: ''
  name: Compiler
  type: string
- container: ''
  name: ExtraBuildInfo
  type: string
- container: ''
  name: GitCommit
  type: string
- container: ''
  name: GitTag
  type: string
- container: ''
  name: GitTreeState
  type: string
- container: ''
  name: GoVersion
  type: string
- container: ''
  name: HelmVersion
  type: string
- container: ''
  name: JsonnetVersion
  type: string
- container: ''
  name: KubectlVersion
  type: string
- container: ''
  name: KustomizeVersion
  type: string
- container: ''
  name: Platform
  type: string
- container: ''
  name: Version
  type: string
property_count: 13
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-version-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"versionVersionMessage\": \"argocd:versionVersionMessage\",\n    \"BuildDate\": {\n      \"@id\": \"argocd:BuildDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Compiler\": {\n      \"@id\": \"argocd:Compiler\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExtraBuildInfo\": {\n      \"@id\": \"argocd:ExtraBuildInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GitCommit\": {\n      \"@id\": \"argocd:GitCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GitTag\": {\n      \"@id\": \"argocd:GitTag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GitTreeState\": {\n      \"@id\": \"argocd:GitTreeState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GoVersion\": {\n      \"@id\": \"argocd:GoVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"HelmVersion\": {\n      \"@id\": \"argocd:HelmVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JsonnetVersion\": {\n      \"@id\": \"argocd:JsonnetVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KubectlVersion\": {\n      \"@id\": \"argocd:KubectlVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KustomizeVersion\": {\n      \"@id\": \"argocd:KustomizeVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Platform\": {\n      \"@id\": \"argocd:Platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"argocd:Version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-version-context.jsonld
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
