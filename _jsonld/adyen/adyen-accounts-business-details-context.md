---
class_count: 1
classes:
- BusinessDetails
context_file: json-ld/adyen-accounts-business-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-business-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Business Details from Adyen.
layout: jsonld
name: Adyen Accounts Business Details Context
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
  name: doingBusinessAs
  type: string
- container: ''
  name: legalBusinessName
  type: string
- container: set
  name: listedUltimateParentCompany
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: set
  name: shareholders
  type: string
- container: set
  name: signatories
  type: string
- container: ''
  name: stockExchange
  type: string
- container: ''
  name: stockNumber
  type: string
- container: ''
  name: stockTicker
  type: string
- container: ''
  name: taxId
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-business-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BusinessDetails\": \"adyen:BusinessDetails\",\n    \"doingBusinessAs\": {\n      \"@id\": \"adyen:doingBusinessAs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalBusinessName\": {\n      \"@id\": \"adyen:legalBusinessName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listedUltimateParentCompany\": {\n      \"@id\": \"adyen:listedUltimateParentCompany\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"adyen:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholders\": {\n      \"@id\": \"adyen:shareholders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatories\": {\n      \"@id\":\
  \ \"adyen:signatories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockExchange\": {\n      \"@id\": \"adyen:stockExchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockNumber\": {\n      \"@id\": \"adyen:stockNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockTicker\": {\n      \"@id\": \"adyen:stockTicker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"adyen:taxId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-business-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
