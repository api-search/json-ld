---
class_count: 1
classes:
- CheckData
context_file: json-ld/adyen-terminal-check-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-check-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Check Data from Adyen.
layout: jsonld
name: Adyen Terminal Check Data Context
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
  name: BankID
  type: string
- container: ''
  name: AccountNumber
  type: string
- container: ''
  name: CheckNumber
  type: string
- container: ''
  name: TrackData
  type: string
- container: ''
  name: CheckCardNumber
  type: string
- container: ''
  name: TypeCode
  type: string
- container: ''
  name: Country
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-check-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckData\": \"adyen:CheckData\",\n    \"BankID\": {\n      \"@id\": \"adyen:BankID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountNumber\": {\n      \"@id\": \"adyen:AccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckNumber\": {\n      \"@id\": \"adyen:CheckNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackData\": {\n      \"@id\": \"adyen:TrackData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckCardNumber\": {\n      \"@id\": \"adyen:CheckCardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TypeCode\": {\n      \"@id\": \"adyen:TypeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"adyen:Country\",\n      \"@type\": \"xsd:string\"\n\
  \    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-check-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
