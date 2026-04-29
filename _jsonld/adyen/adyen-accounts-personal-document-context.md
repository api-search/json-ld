---
class_count: 1
classes:
- PersonalDocumentData
context_file: json-ld/adyen-accounts-personal-document-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-personal-document-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Personal Document from Adyen.
layout: jsonld
name: Adyen Accounts Personal Document Context
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
  name: expirationDate
  type: string
- container: ''
  name: issuerCountry
  type: string
- container: ''
  name: issuerState
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-personal-document-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PersonalDocumentData\": \"adyen:PersonalDocumentData\",\n    \"expirationDate\": {\n      \"@id\": \"adyen:expirationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerCountry\": {\n      \"@id\": \"adyen:issuerCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerState\": {\n      \"@id\": \"adyen:issuerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-personal-document-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
