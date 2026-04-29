---
class_count: 1
classes:
- Timeouts
context_file: json-ld/adyen-management-timeouts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-timeouts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Timeouts from Adyen.
layout: jsonld
name: Adyen Management Timeouts Context
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
  name: fromActiveToSleep
  type: integer
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-timeouts-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Timeouts\": \"adyen:Timeouts\",\n    \"fromActiveToSleep\": {\n      \"@id\": \"adyen:fromActiveToSleep\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-timeouts-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
