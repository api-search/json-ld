---
class_count: 1
classes:
- Duration
context_file: json-ld/adyen-configuration-duration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-duration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Duration from Adyen.
layout: jsonld
name: Adyen Configuration Duration Context
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
  name: unit
  type: string
- container: ''
  name: value
  type: integer
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-duration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Duration\": \"adyen:Duration\",\n    \"unit\": {\n      \"@id\": \"adyen:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-duration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
