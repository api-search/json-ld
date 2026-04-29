---
class_count: 2
classes:
- UpdateStoreRequest
- description
context_file: json-ld/adyen-management-update-store-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-store-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Update Store from Adyen.
layout: jsonld
name: Adyen Management Update Store Context
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
- container: set
  name: businessLineIds
  type: string
- container: ''
  name: externalReferenceId
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: splitConfiguration
  type: string
- container: ''
  name: status
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-update-store-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateStoreRequest\": \"adyen:UpdateStoreRequest\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessLineIds\": {\n      \"@id\": \"adyen:businessLineIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"externalReferenceId\": {\n      \"@id\": \"adyen:externalReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitConfiguration\": {\n      \"@id\": \"adyen:splitConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n    \
  \  \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-store-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
