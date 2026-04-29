---
class_count: 33
classes:
- Instance
- id
- name
- gpuType
- gpuCount
- status
- region
- imageId
- InstanceInput
- InstanceList
- instances
- total
- InstanceMetrics
- instanceId
- gpuUtilization
- memoryUsed
- memoryTotal
- temperature
- powerDraw
- Model
- framework
- endpoint
- ModelInput
- modelId
- ModelList
- models
- Credits
- balance
- used
- currency
- ErrorResponse
- code
- message
context_file: json-ld/amd-developer-cloud-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/json-ld/amd-developer-cloud-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amd Developer Cloud Api from Advanced Micro Devices.
layout: jsonld
name: Amd Developer Cloud Api Context
namespaces:
- prefix: amd
  uri: https://developer.amd.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: expiresAt
  type: dateTime
property_count: 2
provider_name: Advanced Micro Devices
provider_slug: advanced-micro-devices
slug: amd-developer-cloud-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amd\": \"https://developer.amd.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Instance\": \"amd:ComputeInstance\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"gpuType\": \"amd:gpuType\",\n    \"gpuCount\": \"amd:gpuCount\",\n    \"status\": \"schema:status\",\n    \"region\": \"amd:region\",\n    \"imageId\": \"amd:imageId\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"InstanceInput\": \"amd:InstanceInput\",\n    \"InstanceList\": \"amd:InstanceList\",\n    \"instances\": \"amd:instances\",\n    \"total\": \"amd:total\",\n    \"InstanceMetrics\": \"amd:InstanceMetrics\",\n    \"instanceId\": \"amd:instanceId\",\n    \"gpuUtilization\": \"amd:gpuUtilization\",\n    \"memoryUsed\": \"amd:memoryUsed\",\n    \"memoryTotal\": \"amd:memoryTotal\",\n    \"temperature\": \"amd:temperature\"\
  ,\n    \"powerDraw\": \"amd:powerDraw\",\n    \"Model\": \"amd:AIModel\",\n    \"framework\": \"amd:framework\",\n    \"endpoint\": \"schema:url\",\n    \"ModelInput\": \"amd:ModelInput\",\n    \"modelId\": \"amd:modelId\",\n    \"ModelList\": \"amd:ModelList\",\n    \"models\": \"amd:models\",\n    \"Credits\": \"amd:Credits\",\n    \"balance\": \"amd:creditBalance\",\n    \"used\": \"amd:creditUsed\",\n    \"currency\": \"schema:currency\",\n    \"expiresAt\": {\n      \"@id\": \"amd:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ErrorResponse\": \"amd:ErrorResponse\",\n    \"code\": \"amd:errorCode\",\n    \"message\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/json-ld/amd-developer-cloud-api-context.jsonld
tags:
- AI
- Cloud Computing
- GPU
- HPC
- Machine Learning
- Semiconductor
- JSON-LD
- Linked Data
- Semantic Web
---
