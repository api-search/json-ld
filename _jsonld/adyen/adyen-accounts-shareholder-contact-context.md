---
class_count: 3
classes:
- ShareholderContact
- email
- name
context_file: json-ld/adyen-accounts-shareholder-contact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-shareholder-contact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Shareholder Contact from Adyen.
layout: jsonld
name: Adyen Accounts Shareholder Contact Context
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
  name: address
  type: string
- container: ''
  name: fullPhoneNumber
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: personalData
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: shareholderCode
  type: string
- container: ''
  name: shareholderReference
  type: string
- container: ''
  name: shareholderType
  type: string
- container: ''
  name: webAddress
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-shareholder-contact-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ShareholderContact\": \"adyen:ShareholderContact\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"fullPhoneNumber\": {\n      \"@id\": \"adyen:fullPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTitle\": {\n      \"@id\": \"adyen:jobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"personalData\": {\n      \"@id\": \"adyen:personalData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderCode\": {\n      \"@id\": \"adyen:shareholderCode\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"shareholderReference\": {\n      \"@id\": \"adyen:shareholderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderType\": {\n      \"@id\": \"adyen:shareholderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webAddress\": {\n      \"@id\": \"adyen:webAddress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-shareholder-contact-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
