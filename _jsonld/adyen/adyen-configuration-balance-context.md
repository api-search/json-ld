---
class_count: 1
classes:
- Balance
context_file: json-ld/adyen-configuration-balance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-balance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Balance from Adyen.
layout: jsonld
name: Adyen Configuration Balance Context
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
  name: available
  type: integer
- container: ''
  name: balance
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: pending
  type: integer
- container: ''
  name: reserved
  type: integer
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-balance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Balance\": \"adyen:Balance\",\n    \"available\": {\n      \"@id\": \"adyen:available\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"balance\": {\n      \"@id\": \"adyen:balance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"adyen:pending\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reserved\": {\n      \"@id\": \"adyen:reserved\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-balance-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
