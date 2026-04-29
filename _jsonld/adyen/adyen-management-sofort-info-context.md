---
class_count: 1
classes:
- SofortInfo
context_file: json-ld/adyen-management-sofort-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-sofort-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Sofort Info from Adyen.
layout: jsonld
name: Adyen Management Sofort Info Context
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
  name: currencyCode
  type: string
- container: ''
  name: logo
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-sofort-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SofortInfo\": \"adyen:SofortInfo\",\n    \"currencyCode\": {\n      \"@id\": \"adyen:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"adyen:logo\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-sofort-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
