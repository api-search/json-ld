---
class_count: 1
classes:
- ErrorFieldType
context_file: json-ld/adyen-notification-configurations-error-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-error-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Notification Configurations Error from Adyen.
layout: jsonld
name: Adyen Notification Configurations Error Context
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
  name: errorCode
  type: integer
- container: ''
  name: errorDescription
  type: string
- container: ''
  name: fieldType
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-notification-configurations-error-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorFieldType\": \"adyen:ErrorFieldType\",\n    \"errorCode\": {\n      \"@id\": \"adyen:errorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorDescription\": {\n      \"@id\": \"adyen:errorDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldType\": {\n      \"@id\": \"adyen:fieldType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-notification-configurations-error-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
