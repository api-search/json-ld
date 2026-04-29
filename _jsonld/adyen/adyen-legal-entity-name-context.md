---
class_count: 1
classes:
- Name
context_file: json-ld/adyen-legal-entity-name-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-name-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Name from Adyen.
layout: jsonld
name: Adyen Legal Entity Name Context
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
  name: firstName
  type: string
- container: ''
  name: infix
  type: string
- container: ''
  name: lastName
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-name-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Name\": \"adyen:Name\",\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"infix\": {\n      \"@id\": \"adyen:infix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-name-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
