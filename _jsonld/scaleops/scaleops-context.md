---
class_count: 0
classes: []
context_file: json-ld/scaleops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scaleops/refs/heads/main/json-ld/scaleops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scaleops from ScaleOps.
layout: jsonld
name: Scaleops Context
namespaces:
- prefix: scaleops
  uri: https://scaleops.com/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: k8s
  uri: https://kubernetes.io/vocabulary/
properties:
- container: ''
  name: ScaleOpsWorkload
  type: schema:SoftwareApplication
- container: ''
  name: ScaleOpsCluster
  type: schema:SoftwareApplication
- container: ''
  name: ScaleOpsOptimization
  type: schema:Action
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: cluster
  type: string
- container: list
  name: containers
  type: ''
- container: ''
  name: replicas
  type: integer
- container: ''
  name: optimization_status
  type: string
- container: ''
  name: monthly_cost_current
  type: decimal
- container: ''
  name: monthly_cost_optimized
  type: decimal
- container: ''
  name: monthly_savings
  type: decimal
- container: ''
  name: requests
  type: ''
- container: ''
  name: limits
  type: ''
- container: ''
  name: cpu
  type: string
- container: ''
  name: memory
  type: string
property_count: 17
provider_name: ScaleOps
provider_slug: scaleops
slug: scaleops-context
source_filename: scaleops-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"scaleops\": \"https://scaleops.com/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"k8s\": \"https://kubernetes.io/vocabulary/\",\n\n    \"ScaleOpsWorkload\": {\n      \"@id\": \"scaleops:Workload\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ScaleOpsCluster\": {\n      \"@id\": \"scaleops:Cluster\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ScaleOpsOptimization\": {\n      \"@id\": \"scaleops:Optimization\",\n      \"@type\": \"schema:Action\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"k8s:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cluster\": {\n      \"@id\": \"scaleops:cluster\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"containers\": {\n      \"@id\": \"k8s:containers\",\n      \"@container\": \"@list\"\n    },\n    \"replicas\": {\n      \"@id\": \"k8s:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"optimization_status\": {\n      \"@id\": \"scaleops:optimizationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monthly_cost_current\": {\n      \"@id\": \"scaleops:monthlyCostCurrent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"monthly_cost_optimized\": {\n      \"@id\": \"scaleops:monthlyCostOptimized\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"monthly_savings\": {\n      \"@id\": \"scaleops:monthlySavings\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"requests\": {\n      \"@id\": \"k8s:resourceRequests\"\n    },\n    \"limits\": {\n      \"@id\": \"k8s:resourceLimits\"\n    },\n    \"cpu\": {\n      \"@id\": \"k8s:cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memory\": {\n      \"@id\": \"k8s:memory\",\n      \"@type\": \"xsd:string\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scaleops/refs/heads/main/json-ld/scaleops-context.jsonld
tags:
- Azure
- Cost Optimization
- FinOps
- GCP
- Helm
- Kubernetes
- Resource Management
- JSON-LD
- Linked Data
- Semantic Web
---
