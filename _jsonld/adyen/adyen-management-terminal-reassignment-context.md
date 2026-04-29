---
class_count: 2
classes:
- TerminalReassignmentRequest
- TerminalReassignmentTarget
context_file: json-ld/adyen-management-terminal-reassignment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-reassignment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Terminal Reassignment from Adyen.
layout: jsonld
name: Adyen Management Terminal Reassignment Context
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
  name: companyId
  type: string
- container: ''
  name: inventory
  type: boolean
- container: ''
  name: merchantId
  type: string
- container: ''
  name: storeId
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-terminal-reassignment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TerminalReassignmentRequest\": \"adyen:TerminalReassignmentRequest\",\n    \"TerminalReassignmentTarget\": \"adyen:TerminalReassignmentTarget\",\n    \"companyId\": {\n      \"@id\": \"adyen:companyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventory\": {\n      \"@id\": \"adyen:inventory\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantId\": {\n      \"@id\": \"adyen:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"adyen:storeId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-reassignment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
