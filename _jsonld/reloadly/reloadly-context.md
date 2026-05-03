---
api_specs:
- filename: reloadly-gift-cards-openapi.yml
  format: yaml
  label: Reloadly Gift Cards API
  slug: gift-cards
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/openapi/reloadly-gift-cards-openapi.yml
- filename: reloadly-airtime-openapi.yml
  format: yaml
  label: Reloadly Airtime API
  slug: airtime
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/openapi/reloadly-airtime-openapi.yml
class_count: 9
classes:
- Product
- Order
- Organization
- Country
- name
- description
- url
- identifier
- email
context_file: json-ld/reloadly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/json-ld/reloadly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reloadly from Reloadly.
layout: jsonld
name: Reloadly Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: reloadly
  uri: https://api-evangelist.github.io/reloadly/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: GiftCardProduct
  type: reference
- container: ''
  name: GiftCardOrder
  type: reference
- container: ''
  name: GiftCardCode
  type: reference
- container: ''
  name: AirtimeTopUp
  type: reference
- container: ''
  name: MobileOperator
  type: reference
- container: ''
  name: productId
  type: integer
- container: ''
  name: brandName
  type: string
- container: ''
  name: denominationType
  type: string
- container: ''
  name: discountPercentage
  type: decimal
- container: ''
  name: recipientCurrencyCode
  type: string
- container: ''
  name: senderCurrencyCode
  type: string
- container: ''
  name: transactionId
  type: integer
- container: ''
  name: redemptionCode
  type: string
- container: ''
  name: operatorId
  type: integer
- container: ''
  name: countryCode
  type: string
- container: ''
  name: customIdentifier
  type: string
- container: ''
  name: useLocalAmount
  type: boolean
property_count: 17
provider_name: Reloadly
provider_slug: reloadly
slug: reloadly-context
source_filename: reloadly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"reloadly\": \"https://api-evangelist.github.io/reloadly/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Organization\": \"schema:Organization\",\n    \"Country\": \"schema:Country\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n\n    \"GiftCardProduct\": {\n      \"@id\": \"reloadly:GiftCardProduct\",\n      \"@type\": \"@id\",\n      \"comment\": \"A digital gift card product available through the Reloadly catalog\"\n    },\n    \"GiftCardOrder\": {\n      \"@id\": \"reloadly:GiftCardOrder\",\n      \"@type\": \"@id\",\n      \"comment\": \"A placed and fulfilled digital gift card order\"\n    },\n    \"GiftCardCode\": {\n      \"@id\": \"reloadly:GiftCardCode\"\
  ,\n      \"@type\": \"@id\",\n      \"comment\": \"A digital gift card redemption code delivered to a recipient\"\n    },\n    \"AirtimeTopUp\": {\n      \"@id\": \"reloadly:AirtimeTopUp\",\n      \"@type\": \"@id\",\n      \"comment\": \"A mobile airtime top-up transaction sent to a phone number\"\n    },\n    \"MobileOperator\": {\n      \"@id\": \"reloadly:MobileOperator\",\n      \"@type\": \"@id\",\n      \"comment\": \"A mobile network operator supported by the Reloadly Airtime API\"\n    },\n    \"productId\": {\n      \"@id\": \"reloadly:productId\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Unique Reloadly product identifier\"\n    },\n    \"brandName\": {\n      \"@id\": \"reloadly:brandName\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"The gift card brand name (e.g., Amazon, Apple, Netflix)\"\n    },\n    \"denominationType\": {\n      \"@id\": \"reloadly:denominationType\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"Whether the product\
  \ uses FIXED or RANGE denominations\"\n    },\n    \"discountPercentage\": {\n      \"@id\": \"reloadly:discountPercentage\",\n      \"@type\": \"xsd:decimal\",\n      \"comment\": \"Percentage discount on face value\"\n    },\n    \"recipientCurrencyCode\": {\n      \"@id\": \"reloadly:recipientCurrencyCode\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"ISO 4217 currency code for the gift card recipient\"\n    },\n    \"senderCurrencyCode\": {\n      \"@id\": \"reloadly:senderCurrencyCode\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"ISO 4217 currency code for the sender\"\n    },\n    \"transactionId\": {\n      \"@id\": \"reloadly:transactionId\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Unique transaction identifier\"\n    },\n    \"redemptionCode\": {\n      \"@id\": \"reloadly:redemptionCode\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"The digital code used to redeem a gift card\"\n    },\n    \"operatorId\": {\n      \"@id\"\
  : \"reloadly:operatorId\",\n      \"@type\": \"xsd:integer\",\n      \"comment\": \"Unique mobile network operator identifier\"\n    },\n    \"countryCode\": {\n      \"@id\": \"reloadly:countryCode\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"ISO 3166-1 alpha-2 country code\"\n    },\n    \"customIdentifier\": {\n      \"@id\": \"reloadly:customIdentifier\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"Partner-provided custom reference identifier for tracking\"\n    },\n    \"useLocalAmount\": {\n      \"@id\": \"reloadly:useLocalAmount\",\n      \"@type\": \"xsd:boolean\",\n      \"comment\": \"Whether the top-up amount is in local or international currency\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reloadly/refs/heads/main/json-ld/reloadly-context.jsonld
tags:
- Gift Cards
- Payments
- Airtime
- Mobile Top-Up
- Rewards
- Incentives
- JSON-LD
- Linked Data
- Semantic Web
---
