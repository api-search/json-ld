---
api_specs:
- filename: allianz-future-cloud-platform-services.yaml
  format: yaml
  label: Allianz Future Cloud Platform Services API
  slug: platform-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/openapi/allianz-future-cloud-platform-services.yaml
class_count: 12
classes:
- Deployment
- MetricsResponse
- InfrastructureResource
- NamespaceList
- DeployServiceRequest
- DeploymentList
- ResourceRequirements
- Service
- RegisterServiceRequest
- ServiceList
- ProvisionResourceRequest
- Namespace
context_file: json-ld/allianz-future-cloud-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/json-ld/allianz-future-cloud-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Future Cloud Platform from Allianz Future Cloud Platform.
layout: jsonld
name: Allianz Future Cloud Platform Context
namespaces:
- prefix: allianz
  uri: https://platform.allianz.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: deploymentId
  type: string
- container: ''
  name: serviceId
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: strategy
  type: string
- container: ''
  name: deployedAt
  type: dateTime
- container: ''
  name: deployedBy
  type: string
- container: ''
  name: initiatedAt
  type: dateTime
- container: ''
  name: timeRangeMinutes
  type: integer
- container: ''
  name: cpuUtilization
  type: double
- container: ''
  name: memoryUtilization
  type: double
- container: ''
  name: requestRate
  type: double
- container: ''
  name: errorRate
  type: double
- container: ''
  name: p99LatencyMs
  type: integer
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: total
  type: integer
- container: set
  name: items
  type: string
- container: ''
  name: cpu
  type: string
- container: ''
  name: memory
  type: string
- container: ''
  name: cpuLimit
  type: string
- container: ''
  name: memoryLimit
  type: string
- container: ''
  name: replicas
  type: integer
- container: ''
  name: language
  type: string
- container: ''
  name: repositoryUrl
  type: reference
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: resourceRequirements
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: namespaceId
  type: string
- container: ''
  name: team
  type: string
- container: ''
  name: serviceCount
  type: integer
property_count: 35
provider_name: Allianz Future Cloud Platform
provider_slug: allianz-future-cloud-platform
slug: allianz-future-cloud-platform-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"allianz\": \"https://platform.allianz.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Deployment\": \"allianz:Deployment\",\n    \"MetricsResponse\": \"allianz:MetricsResponse\",\n    \"InfrastructureResource\": \"allianz:InfrastructureResource\",\n    \"NamespaceList\": \"allianz:NamespaceList\",\n    \"DeployServiceRequest\": \"allianz:DeployServiceRequest\",\n    \"DeploymentList\": \"allianz:DeploymentList\",\n    \"ResourceRequirements\": \"allianz:ResourceRequirements\",\n    \"Service\": \"allianz:Service\",\n    \"RegisterServiceRequest\": \"allianz:RegisterServiceRequest\",\n    \"ServiceList\": \"allianz:ServiceList\",\n    \"ProvisionResourceRequest\": \"allianz:ProvisionResourceRequest\",\n    \"Namespace\": \"allianz:Namespace\",\n    \"deploymentId\": {\n      \"@id\": \"allianz:deployment_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceId\": {\n      \"@id\": \"allianz:service_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"allianz:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"allianz:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"allianz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strategy\": {\n      \"@id\": \"allianz:strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deployedAt\": {\n      \"@id\": \"allianz:deployed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deployedBy\": {\n      \"@id\": \"allianz:deployed_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initiatedAt\": {\n      \"@id\": \"allianz:initiated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeRangeMinutes\": {\n      \"@id\": \"allianz:time_range_minutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cpuUtilization\": {\n\
  \      \"@id\": \"allianz:cpu_utilization\",\n      \"@type\": \"xsd:double\"\n    },\n    \"memoryUtilization\": {\n      \"@id\": \"allianz:memory_utilization\",\n      \"@type\": \"xsd:double\"\n    },\n    \"requestRate\": {\n      \"@id\": \"allianz:request_rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"errorRate\": {\n      \"@id\": \"allianz:error_rate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"p99LatencyMs\": {\n      \"@id\": \"allianz:p99_latency_ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resourceId\": {\n      \"@id\": \"allianz:resource_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"allianz:resource_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"allianz:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": {\n      \"@id\": \"allianz:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"allianz:created_at\",\n  \
  \    \"@type\": \"xsd:dateTime\"\n    },\n    \"total\": {\n      \"@id\": \"allianz:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"allianz:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpu\": {\n      \"@id\": \"allianz:cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memory\": {\n      \"@id\": \"allianz:memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuLimit\": {\n      \"@id\": \"allianz:cpu_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryLimit\": {\n      \"@id\": \"allianz:memory_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replicas\": {\n      \"@id\": \"allianz:replicas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"language\": {\n      \"@id\": \"allianz:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryUrl\": {\n      \"@id\": \"allianz:repository_url\",\n      \"@type\": \"@id\"\n    },\n    \"modifiedAt\": {\n      \"@id\"\
  : \"allianz:modified_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resourceRequirements\": {\n      \"@id\": \"allianz:resource_requirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"allianz:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespaceId\": {\n      \"@id\": \"allianz:namespace_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team\": {\n      \"@id\": \"allianz:team\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceCount\": {\n      \"@id\": \"allianz:service_count\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-future-cloud-platform/refs/heads/main/json-ld/allianz-future-cloud-platform-context.jsonld
tags:
- Cloud Platform
- Enterprise
- Financial Services
- Insurance
- Platform Engineering
- Kubernetes
- JSON-LD
- Linked Data
- Semantic Web
---
