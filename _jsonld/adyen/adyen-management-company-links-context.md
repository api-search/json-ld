---
class_count: 1
classes:
- CompanyLinks
context_file: json-ld/adyen-management-company-links-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-company-links-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Company Links from Adyen.
layout: jsonld
name: Adyen Management Company Links Context
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
  name: apiCredentials
  type: string
- container: ''
  name: self
  type: string
- container: ''
  name: users
  type: string
- container: ''
  name: webhooks
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-company-links-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CompanyLinks\": \"adyen:CompanyLinks\",\n    \"apiCredentials\": {\n      \"@id\": \"adyen:apiCredentials\",\n      \"@type\": \"xsd:string\"\n    },\n    \"self\": {\n      \"@id\": \"adyen:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"adyen:users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webhooks\": {\n      \"@id\": \"adyen:webhooks\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-company-links-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
