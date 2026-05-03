---
api_specs:
- filename: tremendous-api-openapi.yml
  format: yaml
  label: Tremendous API
  slug: tremendous
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/openapi/tremendous-api-openapi.yml
class_count: 21
classes:
- Order
- Reward
- Product
- Campaign
- Organization
- Member
- Invoice
- FundingSource
- id
- name
- description
- status
- external_id
- category
- email
- role
- payment
- currency_code
- value
- delivery
- method
context_file: json-ld/tremendous-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/json-ld/tremendous-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tremendous from Tremendous.
layout: jsonld
name: Tremendous Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tremendous
  uri: https://tremendous.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: due_at
  type: dateTime
- container: ''
  name: image_url
  type: reference
- container: ''
  name: website
  type: reference
- container: ''
  name: recipient
  type: reference
- container: set
  name: rewards
  type: ''
- container: set
  name: products
  type: ''
- container: set
  name: orders
  type: ''
- container: ''
  name: funding_source_id
  type: reference
- container: ''
  name: denomination
  type: decimal
- container: ''
  name: delivered_at
  type: dateTime
- container: ''
  name: campaign_id
  type: reference
- container: ''
  name: url
  type: reference
- container: set
  name: skus
  type: ''
- container: set
  name: countries
  type: ''
- container: set
  name: currency_codes
  type: ''
property_count: 16
provider_name: Tremendous
provider_slug: tremendous
slug: tremendous-context
source_filename: tremendous-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tremendous\": \"https://tremendous.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Order\": \"schema:Order\",\n    \"Reward\": \"schema:GiveAction\",\n    \"Product\": \"schema:Product\",\n    \"Campaign\": \"tremendous:Campaign\",\n    \"Organization\": \"schema:Organization\",\n    \"Member\": \"schema:Person\",\n    \"Invoice\": \"schema:Invoice\",\n    \"FundingSource\": \"tremendous:FundingSource\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"tremendous:status\",\n    \"external_id\": \"tremendous:externalId\",\n    \"created_at\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"due_at\": { \"@id\": \"schema:expires\", \"@type\": \"xsd:dateTime\" },\n    \"category\": \"schema:category\",\n    \"image_url\": { \"@id\": \"schema:image\", \"@type\": \"\
  @id\" },\n    \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"email\": \"schema:email\",\n    \"role\": \"schema:roleName\",\n\n    \"recipient\": { \"@id\": \"schema:recipient\", \"@type\": \"@id\" },\n    \"rewards\": { \"@id\": \"tremendous:rewards\", \"@container\": \"@set\" },\n    \"products\": { \"@id\": \"tremendous:products\", \"@container\": \"@set\" },\n    \"orders\": { \"@id\": \"tremendous:orders\", \"@container\": \"@set\" },\n\n    \"payment\": \"tremendous:payment\",\n    \"funding_source_id\": { \"@id\": \"tremendous:fundingSourceId\", \"@type\": \"@id\" },\n    \"denomination\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"currency_code\": \"schema:priceCurrency\",\n    \"value\": \"schema:priceSpecification\",\n\n    \"delivery\": \"tremendous:delivery\",\n    \"method\": \"tremendous:deliveryMethod\",\n    \"delivered_at\": { \"@id\": \"schema:dateDelivered\", \"@type\": \"xsd:dateTime\" },\n    \"campaign_id\": { \"@id\":\
  \ \"tremendous:campaignId\", \"@type\": \"@id\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"skus\": { \"@id\": \"tremendous:skus\", \"@container\": \"@set\" },\n    \"countries\": { \"@id\": \"schema:areaServed\", \"@container\": \"@set\" },\n    \"currency_codes\": { \"@id\": \"tremendous:currencyCodes\", \"@container\": \"@set\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tremendous/refs/heads/main/json-ld/tremendous-context.jsonld
tags:
- Employee Incentives
- Global Payouts
- Incentives
- Market Research
- Payouts
- Rewards
- JSON-LD
- Linked Data
- Semantic Web
---
