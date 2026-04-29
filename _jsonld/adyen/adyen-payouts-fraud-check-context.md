---
class_count: 3
classes:
- FraudCheckResult
- FraudCheckResultWrapper
- name
context_file: json-ld/adyen-payouts-fraud-check-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-fraud-check-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Fraud Check from Adyen.
layout: jsonld
name: Adyen Payouts Fraud Check Context
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
- container: ''
  name: checkId
  type: integer
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-fraud-check-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FraudCheckResult\": \"adyen:FraudCheckResult\",\n    \"FraudCheckResultWrapper\": \"adyen:FraudCheckResultWrapper\",\n    \"accountScore\": {\n      \"@id\": \"adyen:accountScore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"checkId\": {\n      \"@id\": \"adyen:checkId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-fraud-check-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
