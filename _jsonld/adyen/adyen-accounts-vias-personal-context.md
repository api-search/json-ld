---
class_count: 1
classes:
- ViasPersonalData
context_file: json-ld/adyen-accounts-vias-personal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-vias-personal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Vias Personal from Adyen.
layout: jsonld
name: Adyen Accounts Vias Personal Context
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
  name: dateOfBirth
  type: string
- container: set
  name: documentData
  type: string
- container: ''
  name: nationality
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-vias-personal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ViasPersonalData\": \"adyen:ViasPersonalData\",\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentData\": {\n      \"@id\": \"adyen:documentData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-vias-personal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
