---
class_count: 1
classes:
- IdentificationData
context_file: json-ld/adyen-legal-entity-identification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-identification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Identification from Adyen.
layout: jsonld
name: Adyen Legal Entity Identification Context
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
  name: cardNumber
  type: string
- container: ''
  name: expiryDate
  type: string
- container: ''
  name: issuerCountry
  type: string
- container: ''
  name: issuerState
  type: string
- container: ''
  name: nationalIdExempt
  type: boolean
- container: ''
  name: number
  type: string
- container: ''
  name: type
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-identification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IdentificationData\": \"adyen:IdentificationData\",\n    \"cardNumber\": {\n      \"@id\": \"adyen:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"adyen:expiryDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerCountry\": {\n      \"@id\": \"adyen:issuerCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerState\": {\n      \"@id\": \"adyen:issuerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationalIdExempt\": {\n      \"@id\": \"adyen:nationalIdExempt\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-identification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
