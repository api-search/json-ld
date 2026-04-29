---
class_count: 0
classes: []
context_file: json-ld/cast-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/json-ld/cast-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cast Ai from CAST AI.
layout: jsonld
name: Cast Ai Context
namespaces:
- prefix: castai
  uri: https://docs.cast.ai/docs/
properties:
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: NodeTemplate
  type: ''
- container: ''
  name: Workload
  type: ''
- container: ''
  name: RebalancingSchedule
  type: ''
- container: ''
  name: CostReport
  type: ''
property_count: 6
provider_name: CAST AI
provider_slug: cast-ai
slug: cast-ai-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"castai\": \"https://docs.cast.ai/docs/\",\n    \"Cluster\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"status\": \"https://schema.org/status\",\n        \"provider\": \"https://schema.org/provider\",\n        \"region\": \"https://schema.org/location\",\n        \"clusterToken\": \"https://schema.org/accessCode\",\n        \"agentStatus\": \"https://schema.org/status\",\n        \"kubernetesVersion\": \"https://schema.org/softwareVersion\",\n        \"nodeCount\": \"https://schema.org/quantity\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"Node\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"instanceType\": \"https://schema.org/category\"\
  ,\n        \"state\": \"https://schema.org/status\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"labels\": \"https://schema.org/keywords\"\n      }\n    },\n    \"NodeTemplate\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"configurationId\": {\n          \"@id\": \"castai:api\",\n          \"@type\": \"@id\"\n        },\n        \"constraints\": \"https://schema.org/valueReference\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Workload\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"clusterId\": {\n          \"@id\": \"castai:api\",\n          \"@type\": \"@id\"\n        },\n        \"namespace\": \"https://schema.org/category\",\n        \"name\": \"https://schema.org/name\"\
  ,\n        \"type\": \"https://schema.org/additionalType\",\n        \"containers\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"RebalancingSchedule\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"clusterId\": {\n          \"@id\": \"castai:api\",\n          \"@type\": \"@id\"\n        },\n        \"schedule\": \"https://schema.org/repeatFrequency\",\n        \"enabled\": \"https://schema.org/actionStatus\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"CostReport\": {\n      \"@id\": \"castai:api\",\n      \"@context\": {\n        \"clusterId\": {\n          \"@id\": \"castai:api\",\n          \"@type\": \"@id\"\n        },\n        \"cpuEfficiency\": \"https://schema.org/value\",\n        \"memoryEfficiency\": \"https://schema.org/value\",\n        \"totalMonthlyCost\": \"https://schema.org/price\",\n        \"optimizedMonthlyCost\": \"https://schema.org/price\"\
  ,\n        \"savingsPercentage\": \"https://schema.org/discount\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/json-ld/cast-ai-context.jsonld
tags:
- Autoscaling
- Cloud Infrastructure
- Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
