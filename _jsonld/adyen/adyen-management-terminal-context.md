---
class_count: 1
classes:
- Terminal
context_file: json-ld/adyen-management-terminal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Terminal from Adyen.
layout: jsonld
name: Adyen Management Terminal Context
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
  name: assignment
  type: string
- container: ''
  name: connectivity
  type: string
- container: ''
  name: firmwareVersion
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: lastActivityAt
  type: dateTime
- container: ''
  name: lastTransactionAt
  type: dateTime
- container: ''
  name: model
  type: string
- container: ''
  name: serialNumber
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-terminal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Terminal\": \"adyen:Terminal\",\n    \"assignment\": {\n      \"@id\": \"adyen:assignment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectivity\": {\n      \"@id\": \"adyen:connectivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firmwareVersion\": {\n      \"@id\": \"adyen:firmwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastActivityAt\": {\n      \"@id\": \"adyen:lastActivityAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastTransactionAt\": {\n      \"@id\": \"adyen:lastTransactionAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"model\": {\n      \"@id\": \"adyen:model\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"adyen:serialNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
