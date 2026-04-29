---
class_count: 1
classes:
- Recurring
context_file: json-ld/adyen-payments-recurring-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-recurring-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Recurring from Adyen.
layout: jsonld
name: Adyen Payments Recurring Context
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
  name: contract
  type: string
- container: ''
  name: recurringDetailName
  type: string
- container: ''
  name: recurringExpiry
  type: dateTime
- container: ''
  name: recurringFrequency
  type: string
- container: ''
  name: tokenService
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-recurring-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Recurring\": \"adyen:Recurring\",\n    \"contract\": {\n      \"@id\": \"adyen:contract\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailName\": {\n      \"@id\": \"adyen:recurringDetailName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringExpiry\": {\n      \"@id\": \"adyen:recurringExpiry\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"recurringFrequency\": {\n      \"@id\": \"adyen:recurringFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenService\": {\n      \"@id\": \"adyen:tokenService\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-recurring-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
