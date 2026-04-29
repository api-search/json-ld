---
class_count: 1
classes:
- CapturedSignature
context_file: json-ld/adyen-terminal-captured-signature-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-captured-signature-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Captured Signature from Adyen.
layout: jsonld
name: Adyen Terminal Captured Signature Context
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
  name: AreaSize
  type: string
- container: set
  name: SignaturePoint
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-captured-signature-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapturedSignature\": \"adyen:CapturedSignature\",\n    \"AreaSize\": {\n      \"@id\": \"adyen:AreaSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SignaturePoint\": {\n      \"@id\": \"adyen:SignaturePoint\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-captured-signature-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
