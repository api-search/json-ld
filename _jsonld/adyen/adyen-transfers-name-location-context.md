---
class_count: 2
classes:
- NameLocation
- name
context_file: json-ld/adyen-transfers-name-location-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-name-location-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Name Location from Adyen.
layout: jsonld
name: Adyen Transfers Name Location Context
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
  name: country
  type: string
- container: ''
  name: countryOfOrigin
  type: string
- container: ''
  name: rawData
  type: string
- container: ''
  name: state
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-name-location-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NameLocation\": \"adyen:NameLocation\",\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryOfOrigin\": {\n      \"@id\": \"adyen:countryOfOrigin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"rawData\": {\n      \"@id\": \"adyen:rawData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"adyen:state\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-name-location-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
