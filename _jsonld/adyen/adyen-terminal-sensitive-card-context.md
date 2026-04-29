---
class_count: 1
classes:
- SensitiveCardData
context_file: json-ld/adyen-terminal-sensitive-card-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sensitive-card-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Sensitive Card from Adyen.
layout: jsonld
name: Adyen Terminal Sensitive Card Context
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
  name: PAN
  type: integer
- container: ''
  name: CardSeqNumb
  type: integer
- container: ''
  name: ExpiryDate
  type: integer
- container: set
  name: TrackData
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-sensitive-card-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SensitiveCardData\": \"adyen:SensitiveCardData\",\n    \"PAN\": {\n      \"@id\": \"adyen:PAN\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CardSeqNumb\": {\n      \"@id\": \"adyen:CardSeqNumb\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ExpiryDate\": {\n      \"@id\": \"adyen:ExpiryDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TrackData\": {\n      \"@id\": \"adyen:TrackData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sensitive-card-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
