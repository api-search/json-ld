---
class_count: 3
classes:
- UsageRecord
- UsageQueryResponse
- UsageQueryRequest
context_file: json-ld/amberflo-metering-usage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-usage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Metering Usage from Amberflo.
layout: jsonld
name: Amberflo Metering Usage Context
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
  name: groupInfo
  type: reference
- container: set
  name: records
  type: reference
- container: ''
  name: clientMeters
  type: reference
- container: ''
  name: meterApiName
  type: string
- container: ''
  name: startTimeInSeconds
  type: integer
- container: ''
  name: endTimeInSeconds
  type: integer
- container: ''
  name: aggregation
  type: string
- container: ''
  name: timeGroupingInterval
  type: string
- container: set
  name: groupBy
  type: string
- container: set
  name: customerFilter
  type: string
- container: ''
  name: filter
  type: reference
property_count: 11
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-metering-usage-context
source_filename: amberflo-metering-usage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UsageRecord\": \"amberflo:UsageRecord\",\n    \"groupInfo\": {\n      \"@id\": \"amberflo:groupInfo\",\n      \"@type\": \"@id\"\n    },\n    \"records\": {\n      \"@id\": \"amberflo:records\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"UsageQueryResponse\": \"amberflo:UsageQueryResponse\",\n    \"clientMeters\": {\n      \"@id\": \"amberflo:clientMeters\",\n      \"@type\": \"@id\"\n    },\n    \"UsageQueryRequest\": \"amberflo:UsageQueryRequest\",\n    \"meterApiName\": {\n      \"@id\": \"amberflo:meterApiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTimeInSeconds\": {\n      \"@id\": \"amberflo:startTimeInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTimeInSeconds\"\
  : {\n      \"@id\": \"amberflo:endTimeInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"aggregation\": {\n      \"@id\": \"amberflo:aggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeGroupingInterval\": {\n      \"@id\": \"amberflo:timeGroupingInterval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupBy\": {\n      \"@id\": \"amberflo:groupBy\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerFilter\": {\n      \"@id\": \"amberflo:customerFilter\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"amberflo:filter\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-usage-context.jsonld
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
