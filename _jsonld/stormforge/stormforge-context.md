---
class_count: 0
classes: []
context_file: json-ld/stormforge-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/json-ld/stormforge-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stormforge from StormForge.
layout: jsonld
name: Stormforge Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: k8s
  uri: https://kubernetes.io/schema/
- prefix: KubernetesCluster
  uri: https://stormforge.io/schema/KubernetesCluster
- prefix: Workload
  uri: https://stormforge.io/schema/Workload
- prefix: Recommendation
  uri: https://stormforge.io/schema/Recommendation
- prefix: ContainerSpec
  uri: https://stormforge.io/schema/ContainerSpec
- prefix: ResourceRequirements
  uri: https://stormforge.io/schema/ResourceRequirements
- prefix: ImpactMetrics
  uri: https://stormforge.io/schema/ImpactMetrics
properties:
- container: ''
  name: clusterName
  type: ''
- container: ''
  name: namespace
  type: ''
- container: ''
  name: workloadName
  type: ''
- container: ''
  name: workloadKind
  type: ''
- container: ''
  name: containerName
  type: ''
- container: ''
  name: cpuRequest
  type: ''
- container: ''
  name: memoryRequest
  type: ''
- container: ''
  name: cpuLimit
  type: ''
- container: ''
  name: memoryLimit
  type: ''
- container: ''
  name: cpuSavingsPercent
  type: decimal
- container: ''
  name: memorySavingsPercent
  type: decimal
- container: ''
  name: estimatedMonthlySavingsUSD
  type: decimal
- container: ''
  name: riskLevel
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: appliedAt
  type: dateTime
- container: ''
  name: hpa
  type: ''
- container: ''
  name: minReplicas
  type: integer
- container: ''
  name: maxReplicas
  type: integer
property_count: 19
provider_name: StormForge
provider_slug: stormforge
slug: stormforge-context
source_filename: stormforge-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://stormforge.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"k8s\": \"https://kubernetes.io/schema/\",\n    \"KubernetesCluster\": \"https://stormforge.io/schema/KubernetesCluster\",\n    \"Workload\": \"https://stormforge.io/schema/Workload\",\n    \"Recommendation\": \"https://stormforge.io/schema/Recommendation\",\n    \"ContainerSpec\": \"https://stormforge.io/schema/ContainerSpec\",\n    \"ResourceRequirements\": \"https://stormforge.io/schema/ResourceRequirements\",\n    \"ImpactMetrics\": \"https://stormforge.io/schema/ImpactMetrics\",\n    \"clusterName\": {\n      \"@id\": \"https://stormforge.io/schema/clusterName\"\n    },\n    \"namespace\": {\n      \"@id\": \"k8s:namespace\"\n    },\n    \"workloadName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"workloadKind\": {\n      \"@id\": \"k8s:kind\"\n    },\n    \"containerName\": {\n      \"@id\"\
  : \"schema:name\"\n    },\n    \"cpuRequest\": {\n      \"@id\": \"https://stormforge.io/schema/cpuRequest\"\n    },\n    \"memoryRequest\": {\n      \"@id\": \"https://stormforge.io/schema/memoryRequest\"\n    },\n    \"cpuLimit\": {\n      \"@id\": \"https://stormforge.io/schema/cpuLimit\"\n    },\n    \"memoryLimit\": {\n      \"@id\": \"https://stormforge.io/schema/memoryLimit\"\n    },\n    \"cpuSavingsPercent\": {\n      \"@id\": \"https://stormforge.io/schema/cpuSavingsPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"memorySavingsPercent\": {\n      \"@id\": \"https://stormforge.io/schema/memorySavingsPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"estimatedMonthlySavingsUSD\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"https://stormforge.io/schema/riskLevel\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"appliedAt\": {\n      \"@id\": \"https://stormforge.io/schema/appliedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"hpa\": {\n      \"@id\": \"https://stormforge.io/schema/horizontalPodAutoscaler\"\n    },\n    \"minReplicas\": {\n      \"@id\": \"https://stormforge.io/schema/minReplicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxReplicas\": {\n      \"@id\": \"https://stormforge.io/schema/maxReplicas\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stormforge/refs/heads/main/json-ld/stormforge-context.jsonld
tags:
- Cloud Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Machine Learning
- Resource Management
- Rightsizing
- JSON-LD
- Linked Data
- Semantic Web
---
