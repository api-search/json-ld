---
class_count: 1
classes:
- DisplayOutput
context_file: json-ld/adyen-terminal-display-output-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-display-output-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Display Output from Adyen.
layout: jsonld
name: Adyen Terminal Display Output Context
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
  name: ResponseRequiredFlag
  type: boolean
- container: ''
  name: MinimumDisplayTime
  type: integer
- container: ''
  name: Device
  type: string
- container: ''
  name: InfoQualify
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
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-display-output-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DisplayOutput\": \"adyen:DisplayOutput\",\n    \"ResponseRequiredFlag\": {\n      \"@id\": \"adyen:ResponseRequiredFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MinimumDisplayTime\": {\n      \"@id\": \"adyen:MinimumDisplayTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Device\": {\n      \"@id\": \"adyen:Device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InfoQualify\": {\n      \"@id\": \"adyen:InfoQualify\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputContent\": {\n      \"@id\": \"adyen:OutputContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MenuEntry\": {\n      \"@id\": \"adyen:MenuEntry\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputSignature\"\
  : {\n      \"@id\": \"adyen:OutputSignature\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-display-output-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
