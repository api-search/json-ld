---
api_specs:
- filename: zendit-api.yml
  format: yaml
  label: Zendit API
  slug: zendit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml
class_count: 2
classes:
- EsimPlanList
- EsimPurchaseRequest
context_file: json-ld/zendit-api-esim-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-esim-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zendit Api Esim from Zendit.
layout: jsonld
name: Zendit Api Esim Context
namespaces:
- prefix: zendit
  uri: https://zendit.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: iccId
  type: string
- container: set
  name: plans
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: offerId
  type: string
property_count: 4
provider_name: Zendit
provider_slug: zendit
slug: zendit-api-esim-context
source_filename: zendit-api-esim-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zendit\": \"https://zendit.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EsimPlanList\": \"zendit:EsimPlanList\",\n    \"EsimPurchaseRequest\": \"zendit:EsimPurchaseRequest\",\n    \"iccId\": {\n      \"@id\": \"zendit:iccId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plans\": {\n      \"@id\": \"zendit:plans\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"zendit:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offerId\": {\n      \"@id\": \"zendit:offerId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-esim-context.jsonld
tags:
- eSIM
- Gift Cards
- Mobile Top-Up
- Payments
- Prepaid
- JSON-LD
- Linked Data
- Semantic Web
---
