---
class_count: 6
classes:
- Product
- Vendor
- PricingResponse
- Webhook
- name
- description
context_file: json-ld/blissfully-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blissfully/refs/heads/main/json-ld/blissfully-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blissfully from Blissfully.
layout: jsonld
name: Blissfully Context
namespaces:
- prefix: vendr
  uri: https://api.vendr.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: website
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: vendor_id
  type: string
- container: ''
  name: product_id
  type: string
- container: set
  name: features
  type: string
- container: set
  name: add_ons
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: fair_price_per_seat
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: confidence
  type: string
- container: ''
  name: negotiation_guidance
  type: string
- container: ''
  name: active
  type: boolean
property_count: 14
provider_name: Blissfully
provider_slug: blissfully
slug: blissfully-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vendr\": \"https://api.vendr.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Product\": \"vendr:Product\",\n    \"Vendor\": \"vendr:Vendor\",\n    \"PricingResponse\": \"vendr:PricingResponse\",\n    \"Webhook\": \"vendr:Webhook\",\n    \"id\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"website\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"category\": {\"@id\": \"vendr:category\", \"@type\": \"xsd:string\"},\n    \"vendor_id\": {\"@id\": \"vendr:vendor_id\", \"@type\": \"xsd:string\"},\n    \"product_id\": {\"@id\": \"vendr:product_id\", \"@type\": \"xsd:string\"},\n    \"features\": {\"@id\": \"vendr:features\", \"@container\": \"@set\"\
  , \"@type\": \"xsd:string\"},\n    \"add_ons\": {\"@id\": \"vendr:add_ons\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"events\": {\"@id\": \"vendr:events\", \"@container\": \"@set\", \"@type\": \"xsd:string\"},\n    \"fair_price_per_seat\": {\"@id\": \"vendr:fair_price_per_seat\", \"@type\": \"xsd:decimal\"},\n    \"currency\": {\"@id\": \"vendr:currency\", \"@type\": \"xsd:string\"},\n    \"confidence\": {\"@id\": \"vendr:confidence\", \"@type\": \"xsd:string\"},\n    \"negotiation_guidance\": {\"@id\": \"vendr:negotiation_guidance\", \"@type\": \"xsd:string\"},\n    \"active\": {\"@id\": \"vendr:active\", \"@type\": \"xsd:boolean\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blissfully/refs/heads/main/json-ld/blissfully-context.jsonld
tags:
- Procurement
- SaaS Discovery
- SaaS Management
- Software Procurement
- Spend Optimization
- Vendor Management
- JSON-LD
- Linked Data
- Semantic Web
---
