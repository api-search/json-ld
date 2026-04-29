---
class_count: 6
classes:
- PaymentIntent
- Transfer
- Account
- FxQuote
- name
- description
context_file: json-ld/airwallex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/json-ld/airwallex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airwallex from Airwallex.
layout: jsonld
name: Airwallex Context
namespaces:
- prefix: airwallex
  uri: https://airwallex.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: merchantOrderId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: sourceAmount
  type: decimal
- container: ''
  name: sourceCurrency
  type: string
- container: ''
  name: targetAmount
  type: decimal
- container: ''
  name: targetCurrency
  type: string
- container: ''
  name: fxRate
  type: decimal
- container: ''
  name: reference
  type: string
- container: ''
  name: fromCurrency
  type: string
- container: ''
  name: toCurrency
  type: string
- container: ''
  name: rate
  type: decimal
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: countryCode
  type: string
- container: ''
  name: primaryCurrency
  type: string
property_count: 19
provider_name: Airwallex
provider_slug: airwallex
slug: airwallex-context
source_filename: airwallex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airwallex\": \"https://airwallex.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentIntent\": \"airwallex:PaymentIntent\",\n    \"Transfer\": \"airwallex:Transfer\",\n    \"Account\": \"airwallex:Account\",\n    \"FxQuote\": \"airwallex:FxQuote\",\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"airwallex:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"airwallex:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"merchantOrderId\": {\n      \"@id\": \"airwallex:merchant_order_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"clientSecret\": {\n      \"@id\": \"airwallex:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAmount\": {\n      \"@id\": \"airwallex:source_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sourceCurrency\": {\n      \"@id\": \"airwallex:source_currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAmount\": {\n      \"@id\": \"airwallex:target_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"targetCurrency\": {\n      \"@id\": \"airwallex:target_currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fxRate\": {\n      \"@id\": \"airwallex:fx_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"reference\": {\n      \"@id\": \"airwallex:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromCurrency\": {\n      \"@id\": \"airwallex:from_currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toCurrency\": {\n      \"@id\": \"airwallex:to_currency\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"rate\": {\n      \"@id\": \"airwallex:rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"airwallex:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"countryCode\": {\n      \"@id\": \"airwallex:country_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryCurrency\": {\n      \"@id\": \"airwallex:primary_currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airwallex/refs/heads/main/json-ld/airwallex-context.jsonld
tags:
- Cross-Border Payments
- FinTech
- Foreign Exchange
- Payments
- Global
- Embedded Finance
- Multi-Currency
- JSON-LD
- Linked Data
- Semantic Web
---
