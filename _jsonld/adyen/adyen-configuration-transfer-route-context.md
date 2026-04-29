---
class_count: 3
classes:
- TransferRouteRequest
- TransferRouteResponse
- TransferRoute
context_file: json-ld/adyen-configuration-transfer-route-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-transfer-route-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Transfer Route from Adyen.
layout: jsonld
name: Adyen Configuration Transfer Route Context
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
  name: balanceAccountId
  type: string
- container: ''
  name: balancePlatform
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: counterparty
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: currency
  type: string
- container: set
  name: priorities
  type: string
- container: set
  name: transferRoutes
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: requirements
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-transfer-route-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransferRouteRequest\": \"adyen:TransferRouteRequest\",\n    \"TransferRouteResponse\": \"adyen:TransferRouteResponse\",\n    \"TransferRoute\": \"adyen:TransferRoute\",\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePlatform\": {\n      \"@id\": \"adyen:balancePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"priorities\": {\n      \"@id\": \"adyen:priorities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transferRoutes\": {\n      \"@id\": \"adyen:transferRoutes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"adyen:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requirements\": {\n      \"@id\": \"adyen:requirements\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-transfer-route-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
