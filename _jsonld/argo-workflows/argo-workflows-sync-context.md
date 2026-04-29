---
api_specs:
- filename: argo-workflows-openapi.json
  format: json
  label: Argo Workflows API
  slug: argo-workflows
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/openapi/argo-workflows-openapi.json
class_count: 4
classes:
- sync.UpdateSyncLimitRequest
- sync.CreateSyncLimitRequest
- sync.SyncLimitResponse
- sync.DeleteSyncLimitResponse
context_file: json-ld/argo-workflows-sync-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-sync-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Sync from Argo Workflows.
layout: jsonld
name: Argo Workflows Sync Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: cmName
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: namespace
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-sync-context
source_filename: argo-workflows-sync-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argo\": \"https://argoproj.github.io/schema/argo-workflows/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sync.UpdateSyncLimitRequest\": \"argo:sync.UpdateSyncLimitRequest\",\n    \"sync.CreateSyncLimitRequest\": \"argo:sync.CreateSyncLimitRequest\",\n    \"sync.SyncLimitResponse\": \"argo:sync.SyncLimitResponse\",\n    \"sync.DeleteSyncLimitResponse\": \"argo:sync.DeleteSyncLimitResponse\",\n    \"cmName\": {\n      \"@id\": \"argo:cmName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"argo:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"argo:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"namespace\": {\n      \"@id\": \"argo:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argo:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-sync-context.jsonld
tags:
- CNCF
- Containers
- Data Processing
- Kubernetes
- Machine Learning
- Open Source
- Workflow Engine
- JSON-LD
- Linked Data
- Semantic Web
---
