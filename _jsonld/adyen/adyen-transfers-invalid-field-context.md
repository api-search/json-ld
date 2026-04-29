---
class_count: 2
classes:
- InvalidField
- name
context_file: json-ld/adyen-transfers-invalid-field-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-invalid-field-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Invalid Field from Adyen.
layout: jsonld
name: Adyen Transfers Invalid Field Context
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
  name: message
  type: string
- container: ''
  name: value
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-invalid-field-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InvalidField\": \"adyen:InvalidField\",\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-invalid-field-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
