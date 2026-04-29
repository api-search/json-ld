---
class_count: 1
classes:
- UpdatableAddress
context_file: json-ld/adyen-management-updatable-address-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-updatable-address-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Updatable Address from Adyen.
layout: jsonld
name: Adyen Management Updatable Address Context
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
  name: line1
  type: string
- container: ''
  name: line2
  type: string
- container: ''
  name: line3
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: stateOrProvince
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-updatable-address-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdatableAddress\": \"adyen:UpdatableAddress\",\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line1\": {\n      \"@id\": \"adyen:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line2\": {\n      \"@id\": \"adyen:line2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line3\": {\n      \"@id\": \"adyen:line3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"adyen:stateOrProvince\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-updatable-address-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
