---
class_count: 1
classes:
- CapitalBalance
context_file: json-ld/adyen-transfers-capital-balance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-capital-balance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Capital Balance from Adyen.
layout: jsonld
name: Adyen Transfers Capital Balance Context
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
  name: currency
  type: string
- container: ''
  name: fee
  type: integer
- container: ''
  name: principal
  type: integer
- container: ''
  name: total
  type: integer
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-capital-balance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapitalBalance\": \"adyen:CapitalBalance\",\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fee\": {\n      \"@id\": \"adyen:fee\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"principal\": {\n      \"@id\": \"adyen:principal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"adyen:total\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-capital-balance-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
