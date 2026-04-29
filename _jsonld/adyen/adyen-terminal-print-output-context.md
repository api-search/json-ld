---
class_count: 1
classes:
- PrintOutput
context_file: json-ld/adyen-terminal-print-output-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-print-output-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Print Output from Adyen.
layout: jsonld
name: Adyen Terminal Print Output Context
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
  name: DocumentQualifier
  type: string
- container: ''
  name: ResponseMode
  type: string
- container: ''
  name: IntegratedPrintFlag
  type: boolean
- container: ''
  name: RequiredSignatureFlag
  type: boolean
- container: ''
  name: OutputContent
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-print-output-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PrintOutput\": \"adyen:PrintOutput\",\n    \"DocumentQualifier\": {\n      \"@id\": \"adyen:DocumentQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResponseMode\": {\n      \"@id\": \"adyen:ResponseMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IntegratedPrintFlag\": {\n      \"@id\": \"adyen:IntegratedPrintFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"RequiredSignatureFlag\": {\n      \"@id\": \"adyen:RequiredSignatureFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"OutputContent\": {\n      \"@id\": \"adyen:OutputContent\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-print-output-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
