---
class_count: 2
classes:
- UpdateMerchantApiCredentialRequest
- description
context_file: json-ld/adyen-management-update-merchant-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-merchant-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Update Merchant Api from Adyen.
layout: jsonld
name: Adyen Management Update Merchant Api Context
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
  name: active
  type: boolean
- container: set
  name: allowedOrigins
  type: string
- container: set
  name: roles
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-update-merchant-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateMerchantApiCredentialRequest\": \"adyen:UpdateMerchantApiCredentialRequest\",\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allowedOrigins\": {\n      \"@id\": \"adyen:allowedOrigins\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"roles\": {\n      \"@id\": \"adyen:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-merchant-api-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
