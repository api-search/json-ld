---
class_count: 1
classes:
- FraudResult
context_file: json-ld/adyen-payments-fraud-result-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-fraud-result-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Fraud Result from Adyen.
layout: jsonld
name: Adyen Payments Fraud Result Context
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
  name: accountScore
  type: integer
- container: set
  name: results
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-fraud-result-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FraudResult\": \"adyen:FraudResult\",\n    \"accountScore\": {\n      \"@id\": \"adyen:accountScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"results\": {\n      \"@id\": \"adyen:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-fraud-result-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
