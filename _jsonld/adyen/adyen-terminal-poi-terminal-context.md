---
class_count: 1
classes:
- POITerminalData
context_file: json-ld/adyen-terminal-poi-terminal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-poi-terminal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Poi Terminal from Adyen.
layout: jsonld
name: Adyen Terminal Poi Terminal Context
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
  name: TerminalEnvironment
  type: string
- container: ''
  name: POICapabilities
  type: string
- container: ''
  name: POIProfile
  type: string
- container: ''
  name: POISerialNumber
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-poi-terminal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"POITerminalData\": \"adyen:POITerminalData\",\n    \"TerminalEnvironment\": {\n      \"@id\": \"adyen:TerminalEnvironment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POICapabilities\": {\n      \"@id\": \"adyen:POICapabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIProfile\": {\n      \"@id\": \"adyen:POIProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POISerialNumber\": {\n      \"@id\": \"adyen:POISerialNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-poi-terminal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
