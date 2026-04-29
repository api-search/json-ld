---
class_count: 1
classes:
- BRLocalAccountIdentification
context_file: json-ld/adyen-configuration-br-local-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-br-local-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Br Local from Adyen.
layout: jsonld
name: Adyen Configuration Br Local Context
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
  name: accountNumber
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: branchNumber
  type: string
- container: ''
  name: type
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-br-local-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BRLocalAccountIdentification\": \"adyen:BRLocalAccountIdentification\",\n    \"accountNumber\": {\n      \"@id\": \"adyen:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"adyen:bankCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branchNumber\": {\n      \"@id\": \"adyen:branchNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-br-local-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
