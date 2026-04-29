---
class_count: 25
classes:
- id
- type
- Api
- Gateway
- Deployment
- Alarm
- Metrics
- name
- description
- version
- status
- host
- port
- gatewayType
- apiCount
- apiId
- currentVersion
- threshold
- condition
- metric
- enabled
- requestCount
- errorCount
- averageLatency
- throughput
context_file: json-ld/apiida-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/json-ld/apiida-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apiida from APIIDA.
layout: jsonld
name: Apiida Context
namespaces:
- prefix: apiida
  uri: https://apiida.com/ns/
properties:
- container: set
  name: targetGateways
  type: reference
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
- container: ''
  name: completedAt
  type: schema:DateTime
- container: set
  name: tags
  type: ''
property_count: 5
provider_name: APIIDA
provider_slug: apiida
slug: apiida-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apiida\": \"https://apiida.com/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Api\": \"apiida:Api\",\n    \"Gateway\": \"apiida:Gateway\",\n    \"Deployment\": \"apiida:Deployment\",\n    \"Alarm\": \"apiida:Alarm\",\n    \"Metrics\": \"apiida:Metrics\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"status\": \"apiida:status\",\n    \"host\": \"apiida:host\",\n    \"port\": \"apiida:port\",\n    \"gatewayType\": \"apiida:gatewayType\",\n    \"apiCount\": \"apiida:apiCount\",\n    \"apiId\": \"apiida:apiId\",\n    \"targetGateways\": {\n      \"@id\": \"apiida:targetGateways\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"currentVersion\": \"apiida:currentVersion\",\n    \"threshold\": \"apiida:threshold\",\n    \"condition\": \"apiida:condition\",\n    \"metric\": \"apiida:metric\",\n \
  \   \"enabled\": \"apiida:enabled\",\n    \"requestCount\": \"apiida:requestCount\",\n    \"errorCount\": \"apiida:errorCount\",\n    \"averageLatency\": \"apiida:averageLatency\",\n    \"throughput\": \"apiida:throughput\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"apiida:completedAt\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/json-ld/apiida-context.jsonld
tags:
- API Gateway
- API Management
- Federated API Management
- Governance
- Layer7
- JSON-LD
- Linked Data
- Semantic Web
---
