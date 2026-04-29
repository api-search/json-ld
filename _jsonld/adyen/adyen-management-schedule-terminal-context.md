---
class_count: 2
classes:
- ScheduleTerminalActionsRequest
- ScheduleTerminalActionsResponse
context_file: json-ld/adyen-management-schedule-terminal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-schedule-terminal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Schedule Terminal from Adyen.
layout: jsonld
name: Adyen Management Schedule Terminal Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: actionDetails
  type: string
- container: ''
  name: scheduledAt
  type: string
- container: ''
  name: storeId
  type: string
- container: set
  name: terminalIds
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: terminalsWithErrors
  type: reference
- container: ''
  name: totalErrors
  type: integer
- container: ''
  name: totalScheduled
  type: integer
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-schedule-terminal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ScheduleTerminalActionsRequest\": \"adyen:ScheduleTerminalActionsRequest\",\n    \"ScheduleTerminalActionsResponse\": \"adyen:ScheduleTerminalActionsResponse\",\n    \"actionDetails\": {\n      \"@id\": \"adyen:actionDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledAt\": {\n      \"@id\": \"adyen:scheduledAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"adyen:storeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminalIds\": {\n      \"@id\": \"adyen:terminalIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"adyen:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminalsWithErrors\"\
  : {\n      \"@id\": \"adyen:terminalsWithErrors\",\n      \"@type\": \"@id\"\n    },\n    \"totalErrors\": {\n      \"@id\": \"adyen:totalErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalScheduled\": {\n      \"@id\": \"adyen:totalScheduled\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-schedule-terminal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
