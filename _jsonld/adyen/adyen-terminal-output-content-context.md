---
class_count: 1
classes:
- OutputContent
context_file: json-ld/adyen-terminal-output-content-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-output-content-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Output Content from Adyen.
layout: jsonld
name: Adyen Terminal Output Content Context
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
  name: OutputFormat
  type: string
- container: ''
  name: PredefinedContent
  type: string
- container: set
  name: OutputText
  type: string
- container: ''
  name: OutputXHTML
  type: string
- container: ''
  name: OutputBarcode
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-output-content-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OutputContent\": \"adyen:OutputContent\",\n    \"OutputFormat\": {\n      \"@id\": \"adyen:OutputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredefinedContent\": {\n      \"@id\": \"adyen:PredefinedContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputText\": {\n      \"@id\": \"adyen:OutputText\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputXHTML\": {\n      \"@id\": \"adyen:OutputXHTML\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputBarcode\": {\n      \"@id\": \"adyen:OutputBarcode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-output-content-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
