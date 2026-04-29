---
class_count: 1
classes:
- AccountEvent
context_file: json-ld/adyen-accounts-account-event-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-account-event-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Account Event from Adyen.
layout: jsonld
name: Adyen Accounts Account Event Context
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
  name: event
  type: string
- container: ''
  name: executionDate
  type: dateTime
- container: ''
  name: reason
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-account-event-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountEvent\": \"adyen:AccountEvent\",\n    \"event\": {\n      \"@id\": \"adyen:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionDate\": {\n      \"@id\": \"adyen:executionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-account-event-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
