---
class_count: 1
classes:
- AbortRequest
context_file: json-ld/adyen-terminal-abort-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-abort-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Abort Request from Adyen.
layout: jsonld
name: Adyen Terminal Abort Request Context
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
  name: MessageReference
  type: string
- container: ''
  name: AbortReason
  type: string
- container: ''
  name: DisplayOutput
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-abort-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AbortRequest\": \"adyen:AbortRequest\",\n    \"MessageReference\": {\n      \"@id\": \"adyen:MessageReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AbortReason\": {\n      \"@id\": \"adyen:AbortReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayOutput\": {\n      \"@id\": \"adyen:DisplayOutput\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-abort-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
