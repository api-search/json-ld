---
class_count: 2
classes:
- UltimateParentCompanyBusinessDetails
- UltimateParentCompany
context_file: json-ld/adyen-accounts-ultimate-parent-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-ultimate-parent-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Ultimate Parent from Adyen.
layout: jsonld
name: Adyen Accounts Ultimate Parent Context
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
  name: legalBusinessName
  type: string
- container: ''
  name: registrationNumber
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
  name: address
  type: string
- container: ''
  name: businessDetails
  type: string
- container: ''
  name: ultimateParentCompanyCode
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-ultimate-parent-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UltimateParentCompanyBusinessDetails\": \"adyen:UltimateParentCompanyBusinessDetails\",\n    \"UltimateParentCompany\": \"adyen:UltimateParentCompany\",\n    \"legalBusinessName\": {\n      \"@id\": \"adyen:legalBusinessName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"adyen:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockExchange\": {\n      \"@id\": \"adyen:stockExchange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockNumber\": {\n      \"@id\": \"adyen:stockNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockTicker\": {\n      \"@id\": \"adyen:stockTicker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"\
  adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessDetails\": {\n      \"@id\": \"adyen:businessDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ultimateParentCompanyCode\": {\n      \"@id\": \"adyen:ultimateParentCompanyCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-ultimate-parent-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
