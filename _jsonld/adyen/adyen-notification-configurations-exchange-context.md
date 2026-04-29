---
class_count: 1
classes:
- ExchangeMessage
context_file: json-ld/adyen-notification-configurations-exchange-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-exchange-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Notification Configurations Exchange from Adyen.
layout: jsonld
name: Adyen Notification Configurations Exchange Context
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
  name: messageCode
  type: string
- container: ''
  name: messageDescription
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-notification-configurations-exchange-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExchangeMessage\": \"adyen:ExchangeMessage\",\n    \"messageCode\": {\n      \"@id\": \"adyen:messageCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageDescription\": {\n      \"@id\": \"adyen:messageDescription\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-exchange-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
