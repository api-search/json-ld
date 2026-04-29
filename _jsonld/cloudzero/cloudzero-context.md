---
class_count: 2
classes:
- name
- description
context_file: json-ld/cloudzero-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/json-ld/cloudzero-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudzero from CloudZero.
layout: jsonld
name: Cloudzero Context
namespaces:
- prefix: cloudzero
  uri: https://api.cloudzero.com/v2/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: costType
  type: string
- container: ''
  name: granularity
  type: string
- container: ''
  name: groupBy
  type: string
- container: ''
  name: viewId
  type: string
- container: ''
  name: budgetAmount
  type: double
- container: ''
  name: budgetPeriod
  type: string
- container: ''
  name: threshold
  type: double
- container: ''
  name: streamName
  type: string
- container: ''
  name: telemetryValue
  type: double
- container: ''
  name: connectionId
  type: string
- container: ''
  name: lineItemCost
  type: double
property_count: 11
provider_name: CloudZero
provider_slug: cloudzero
slug: cloudzero-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cloudzero\": \"https://api.cloudzero.com/v2/\",\n    \"costType\": {\n      \"@id\": \"cloudzero:costType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"granularity\": {\n      \"@id\": \"cloudzero:granularity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupBy\": {\n      \"@id\": \"cloudzero:groupBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewId\": {\n      \"@id\": \"cloudzero:viewId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"budgetAmount\": {\n      \"@id\": \"cloudzero:budgetAmount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"budgetPeriod\": {\n      \"@id\": \"cloudzero:budgetPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threshold\": {\n      \"@id\": \"cloudzero:threshold\",\n      \"@type\": \"xsd:double\"\n    },\n    \"streamName\": {\n      \"@id\": \"cloudzero:streamName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telemetryValue\": {\n   \
  \   \"@id\": \"cloudzero:telemetryValue\",\n      \"@type\": \"xsd:double\"\n    },\n    \"connectionId\": {\n      \"@id\": \"cloudzero:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItemCost\": {\n      \"@id\": \"cloudzero:lineItemCost\",\n      \"@type\": \"xsd:double\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudzero/refs/heads/main/json-ld/cloudzero-context.jsonld
tags:
- Budgets
- Cloud Cost Management
- Cost Allocation
- Cost Optimization
- FinOps
- Telemetry
- Unit Economics
- JSON-LD
- Linked Data
- Semantic Web
---
