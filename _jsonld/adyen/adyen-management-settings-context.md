---
class_count: 1
classes:
- Settings
context_file: json-ld/adyen-management-settings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-settings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Settings from Adyen.
layout: jsonld
name: Adyen Management Settings Context
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
  name: band
  type: string
- container: ''
  name: roaming
  type: boolean
- container: ''
  name: timeout
  type: integer
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-settings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Settings\": \"adyen:Settings\",\n    \"band\": {\n      \"@id\": \"adyen:band\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roaming\": {\n      \"@id\": \"adyen:roaming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timeout\": {\n      \"@id\": \"adyen:timeout\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-settings-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
