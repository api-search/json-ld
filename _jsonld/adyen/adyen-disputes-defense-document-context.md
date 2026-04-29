---
class_count: 2
classes:
- DefenseDocument
- DefenseDocumentType
context_file: json-ld/adyen-disputes-defense-document-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-disputes-defense-document-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Disputes Defense Document from Adyen.
layout: jsonld
name: Adyen Disputes Defense Document Context
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
  name: content
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: defenseDocumentTypeCode
  type: string
- container: ''
  name: available
  type: boolean
- container: ''
  name: requirementLevel
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-disputes-defense-document-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DefenseDocument\": \"adyen:DefenseDocument\",\n    \"DefenseDocumentType\": \"adyen:DefenseDocumentType\",\n    \"content\": {\n      \"@id\": \"adyen:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"adyen:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defenseDocumentTypeCode\": {\n      \"@id\": \"adyen:defenseDocumentTypeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"available\": {\n      \"@id\": \"adyen:available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requirementLevel\": {\n      \"@id\": \"adyen:requirementLevel\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-disputes-defense-document-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
