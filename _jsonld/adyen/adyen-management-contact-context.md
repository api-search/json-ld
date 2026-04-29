---
class_count: 2
classes:
- Contact
- email
context_file: json-ld/adyen-management-contact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-contact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Contact from Adyen.
layout: jsonld
name: Adyen Management Contact Context
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
- container: ''
  name: phoneNumber
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-contact-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Contact\": \"adyen:Contact\",\n    \"email\": \"schema:email\",\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"infix\": {\n      \"@id\": \"adyen:infix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-contact-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
