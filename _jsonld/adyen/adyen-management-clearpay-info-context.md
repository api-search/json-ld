---
class_count: 1
classes:
- ClearpayInfo
context_file: json-ld/adyen-management-clearpay-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-clearpay-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Clearpay Info from Adyen.
layout: jsonld
name: Adyen Management Clearpay Info Context
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
  name: supportUrl
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-clearpay-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ClearpayInfo\": \"adyen:ClearpayInfo\",\n    \"supportUrl\": {\n      \"@id\": \"adyen:supportUrl\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-clearpay-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
