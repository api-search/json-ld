---
api_specs:
- filename: grapes-finance-openapi.yml
  format: yaml
  label: Grapes Finance Core API (Master Vintner)
  slug: grapes-finance-core-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/openapi/grapes-finance-openapi.yml
- filename: grapes-finance-openapi.yml
  format: yaml
  label: Grapes Finance Organizations API (Vineyard Manager)
  slug: grapes-finance-organizations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/openapi/grapes-finance-openapi.yml
class_count: 10
classes:
- Order
- Wallet
- User
- Organization
- id
- type
- sourceAsset
- destinationAsset
- status
- address
context_file: json-ld/grapes-finance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/json-ld/grapes-finance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Grapes Finance from Grapes Finance.
layout: jsonld
name: Grapes Finance Context
namespaces:
- prefix: grapes
  uri: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/json-ld/grapes-finance-context.jsonld#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: decimal
- container: ''
  name: chain
  type: '@vocab'
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: settledAt
  type: dateTime
property_count: 4
provider_name: Grapes Finance
provider_slug: grapes-finance
slug: grapes-finance-context
source_filename: grapes-finance-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"grapes\": \"https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/json-ld/grapes-finance-context.jsonld#\",\n    \"Order\": \"grapes:Order\",\n    \"Wallet\": \"grapes:Wallet\",\n    \"User\": \"grapes:User\",\n    \"Organization\": \"schema:Organization\",\n    \"id\": \"@id\",\n    \"type\": \"grapes:orderType\",\n    \"sourceAsset\": \"grapes:sourceAsset\",\n    \"destinationAsset\": \"grapes:destinationAsset\",\n    \"amount\": {\n      \"@id\": \"grapes:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": \"grapes:status\",\n    \"chain\": {\n      \"@id\": \"grapes:chain\",\n      \"@type\": \"@vocab\"\n    },\n    \"address\": \"grapes:walletAddress\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"settledAt\": {\n      \"@id\": \"grapes:settledAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/json-ld/grapes-finance-context.jsonld
tags:
- Stablecoin
- Onramp
- Offramp
- Fiat
- Payments
- Cryptocurrency
- Embedded Finance
- JSON-LD
- Linked Data
- Semantic Web
---
