---
class_count: 2
classes:
- SourceOfFunds
- description
context_file: json-ld/adyen-legal-entity-source-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-source-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Source from Adyen.
layout: jsonld
name: Adyen Legal Entity Source Context
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
  name: acquiringBusinessLineId
  type: string
- container: ''
  name: adyenProcessedFunds
  type: boolean
- container: ''
  name: type
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-source-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SourceOfFunds\": \"adyen:SourceOfFunds\",\n    \"acquiringBusinessLineId\": {\n      \"@id\": \"adyen:acquiringBusinessLineId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adyenProcessedFunds\": {\n      \"@id\": \"adyen:adyenProcessedFunds\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": \"schema:description\",\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-source-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
