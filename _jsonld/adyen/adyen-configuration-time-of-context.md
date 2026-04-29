---
class_count: 2
classes:
- TimeOfDayRestriction
- TimeOfDay
context_file: json-ld/adyen-configuration-time-of-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-time-of-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Time Of from Adyen.
layout: jsonld
name: Adyen Configuration Time Of Context
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
  name: operation
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: startTime
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-time-of-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TimeOfDayRestriction\": \"adyen:TimeOfDayRestriction\",\n    \"TimeOfDay\": \"adyen:TimeOfDay\",\n    \"operation\": {\n      \"@id\": \"adyen:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"adyen:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"adyen:startTime\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-time-of-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
