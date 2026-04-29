---
class_count: 1
classes:
- MessageReference
context_file: json-ld/adyen-terminal-message-reference-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-message-reference-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Message Reference from Adyen.
layout: jsonld
name: Adyen Terminal Message Reference Context
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
  name: MessageCategory
  type: string
- container: ''
  name: ServiceID
  type: string
- container: ''
  name: DeviceID
  type: string
- container: ''
  name: SaleID
  type: string
- container: ''
  name: POIID
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-message-reference-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MessageReference\": \"adyen:MessageReference\",\n    \"MessageCategory\": {\n      \"@id\": \"adyen:MessageCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceID\": {\n      \"@id\": \"adyen:ServiceID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceID\": {\n      \"@id\": \"adyen:DeviceID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleID\": {\n      \"@id\": \"adyen:SaleID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIID\": {\n      \"@id\": \"adyen:POIID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-message-reference-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
