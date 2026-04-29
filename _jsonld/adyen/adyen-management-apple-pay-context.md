---
class_count: 1
classes:
- ApplePayInfo
context_file: json-ld/adyen-management-apple-pay-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-apple-pay-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Apple Pay from Adyen.
layout: jsonld
name: Adyen Management Apple Pay Context
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
- container: set
  name: domains
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-apple-pay-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApplePayInfo\": \"adyen:ApplePayInfo\",\n    \"domains\": {\n      \"@id\": \"adyen:domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-apple-pay-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
