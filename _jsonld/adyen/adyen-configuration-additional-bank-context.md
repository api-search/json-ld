---
class_count: 1
classes:
- AdditionalBankIdentification
context_file: json-ld/adyen-configuration-additional-bank-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-additional-bank-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Additional Bank from Adyen.
layout: jsonld
name: Adyen Configuration Additional Bank Context
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
  name: code
  type: string
- container: ''
  name: type
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-additional-bank-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalBankIdentification\": \"adyen:AdditionalBankIdentification\",\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-additional-bank-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
