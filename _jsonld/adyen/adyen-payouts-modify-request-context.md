---
class_count: 1
classes:
- ModifyRequest
context_file: json-ld/adyen-payouts-modify-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-modify-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Modify Request from Adyen.
layout: jsonld
name: Adyen Payouts Modify Request Context
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
  name: additionalData
  type: reference
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: originalReference
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-modify-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ModifyRequest\": \"adyen:ModifyRequest\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalReference\": {\n      \"@id\": \"adyen:originalReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-modify-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
