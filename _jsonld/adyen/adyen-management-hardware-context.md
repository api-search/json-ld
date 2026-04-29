---
class_count: 1
classes:
- Hardware
context_file: json-ld/adyen-management-hardware-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-hardware-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Hardware from Adyen.
layout: jsonld
name: Adyen Management Hardware Context
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
  name: displayMaximumBackLight
  type: integer
- container: ''
  name: resetTotalsHour
  type: integer
- container: ''
  name: restartHour
  type: integer
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-hardware-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Hardware\": \"adyen:Hardware\",\n    \"displayMaximumBackLight\": {\n      \"@id\": \"adyen:displayMaximumBackLight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"resetTotalsHour\": {\n      \"@id\": \"adyen:resetTotalsHour\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"restartHour\": {\n      \"@id\": \"adyen:restartHour\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-hardware-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
