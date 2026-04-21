---
class_count: 2
classes:
- grpc.gateway.runtime.Error
- grpc.gateway.runtime.StreamError
context_file: json-ld/argo-workflows-grpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/json-ld/argo-workflows-grpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Workflows Grpc from Argo Workflows.
layout: jsonld
name: Argo Workflows Grpc Context
namespaces:
- prefix: argo
  uri: https://argoproj.github.io/schema/argo-workflows/
- prefix: schema
  uri: https://schema.org/
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
property_count: 7
provider_name: Argo Workflows
provider_slug: argo-workflows
slug: argo-workflows-grpc-context
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
