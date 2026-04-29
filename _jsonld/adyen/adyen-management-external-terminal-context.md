---
class_count: 1
classes:
- ExternalTerminalAction
context_file: json-ld/adyen-management-external-terminal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-external-terminal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management External Terminal from Adyen.
layout: jsonld
name: Adyen Management External Terminal Context
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
  name: actionType
  type: string
- container: ''
  name: config
  type: string
- container: ''
  name: confirmedAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: result
  type: string
- container: ''
  name: scheduledAt
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: terminalId
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-external-terminal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExternalTerminalAction\": \"adyen:ExternalTerminalAction\",\n    \"actionType\": {\n      \"@id\": \"adyen:actionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"adyen:config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confirmedAt\": {\n      \"@id\": \"adyen:confirmedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"adyen:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledAt\": {\n      \"@id\": \"adyen:scheduledAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"terminalId\": {\n      \"@id\": \"adyen:terminalId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-external-terminal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
