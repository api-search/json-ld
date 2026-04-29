---
class_count: 1
classes:
- DisableResult
context_file: json-ld/adyen-recurring-disable-result-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-disable-result-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Disable Result from Adyen.
layout: jsonld
name: Adyen Recurring Disable Result Context
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
  name: response
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-disable-result-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DisableResult\": \"adyen:DisableResult\",\n    \"response\": {\n      \"@id\": \"adyen:response\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-disable-result-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
