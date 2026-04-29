---
class_count: 2
classes:
- BulkAddress
- email
context_file: json-ld/adyen-configuration-bulk-address-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-bulk-address-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Bulk Address from Adyen.
layout: jsonld
name: Adyen Configuration Bulk Address Context
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
  name: city
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: houseNumberOrName
  type: string
- container: ''
  name: mobile
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: street
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-bulk-address-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BulkAddress\": \"adyen:BulkAddress\",\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"adyen:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"houseNumberOrName\": {\n      \"@id\": \"adyen:houseNumberOrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobile\": {\n      \"@id\": \"adyen:mobile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"adyen:stateOrProvince\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"adyen:street\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-bulk-address-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
