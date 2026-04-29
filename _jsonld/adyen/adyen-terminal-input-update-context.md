---
class_count: 1
classes:
- InputUpdate
context_file: json-ld/adyen-terminal-input-update-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-input-update-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Input Update from Adyen.
layout: jsonld
name: Adyen Terminal Input Update Context
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
  name: OutputContent
  type: string
- container: set
  name: MenuEntry
  type: string
- container: ''
  name: OutputSignature
  type: string
- container: ''
  name: MinLength
  type: integer
- container: ''
  name: MaxLength
  type: integer
- container: ''
  name: MaxDecimalLength
  type: integer
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-input-update-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InputUpdate\": \"adyen:InputUpdate\",\n    \"MessageReference\": {\n      \"@id\": \"adyen:MessageReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputContent\": {\n      \"@id\": \"adyen:OutputContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MenuEntry\": {\n      \"@id\": \"adyen:MenuEntry\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputSignature\": {\n      \"@id\": \"adyen:OutputSignature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinLength\": {\n      \"@id\": \"adyen:MinLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxLength\": {\n      \"@id\": \"adyen:MaxLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxDecimalLength\": {\n  \
  \    \"@id\": \"adyen:MaxDecimalLength\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-input-update-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
