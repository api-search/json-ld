---
class_count: 1
classes:
- SwishInfo
context_file: json-ld/adyen-management-swish-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-swish-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Swish Info from Adyen.
layout: jsonld
name: Adyen Management Swish Info Context
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
  name: swishNumber
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-swish-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SwishInfo\": \"adyen:SwishInfo\",\n    \"swishNumber\": {\n      \"@id\": \"adyen:swishNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-swish-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
