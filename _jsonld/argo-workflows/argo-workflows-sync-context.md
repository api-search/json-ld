---
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
