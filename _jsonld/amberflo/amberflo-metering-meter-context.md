---
class_count: 3
classes:
- MeterEvent
- MeterDefinition
- MeterDefinitionRequest
context_file: json-ld/amberflo-metering-meter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-meter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Metering Meter from Amberflo.
layout: jsonld
name: Amberflo Metering Meter Context
namespaces:
- prefix: amberflo
  uri: https://amberflo.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: meterApiName
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: meterValue
  type: decimal
- container: ''
  name: meterTimeInMillis
  type: integer
- container: ''
  name: uniqueId
  type: string
- container: set
  name: dimensions
  type: string
- container: ''
  name: values
  type: reference
- container: ''
  name: displayName
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: type
  type: string
property_count: 10
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-metering-meter-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MeterEvent\": \"amberflo:MeterEvent\",\n    \"meterApiName\": {\n      \"@id\": \"amberflo:meterApiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"amberflo:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meterValue\": {\n      \"@id\": \"amberflo:meterValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"meterTimeInMillis\": {\n      \"@id\": \"amberflo:meterTimeInMillis\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"uniqueId\": {\n      \"@id\": \"amberflo:uniqueId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"amberflo:dimensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n \
  \     \"@id\": \"amberflo:values\",\n      \"@type\": \"@id\"\n    },\n    \"MeterDefinition\": \"amberflo:MeterDefinition\",\n    \"displayName\": {\n      \"@id\": \"amberflo:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"amberflo:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amberflo:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MeterDefinitionRequest\": \"amberflo:MeterDefinitionRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-meter-context.jsonld
tags:
- Usage-Based Billing
- Metering
- FinOps
- AI Cost Management
- Billing
- Monetization
- JSON-LD
- Linked Data
- Semantic Web
---
