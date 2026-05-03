---
api_specs:
- filename: synnex-streamone-ion-openapi.yml
  format: yaml
  label: TD SYNNEX StreamOne ION API
  slug: streamone-ion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synnex/refs/heads/main/openapi/synnex-streamone-ion-openapi.yml
class_count: 18
classes:
- Customer
- Subscription
- Order
- Product
- customerId
- companyName
- subscriptionId
- productName
- vendor
- quantity
- subscriptionStatus
- autoRenew
- orderId
- sku
- currency
- totalAmount
- email
- country
context_file: json-ld/synnex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/synnex/refs/heads/main/json-ld/synnex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Synnex from Synnex.
layout: jsonld
name: Synnex Context
namespaces:
- prefix: ion
  uri: https://ion.tdsynnex.com/vocab/
properties:
- container: ''
  name: renewalDate
  type: schema:Date
- container: ''
  name: createdAt
  type: schema:DateTime
property_count: 2
provider_name: Synnex
provider_slug: synnex
slug: synnex-context
source_filename: synnex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ion\": \"https://ion.tdsynnex.com/vocab/\",\n    \"Customer\": \"schema:Organization\",\n    \"Subscription\": \"ion:Subscription\",\n    \"Order\": \"schema:Order\",\n    \"Product\": \"schema:Product\",\n    \"customerId\": \"ion:customerId\",\n    \"companyName\": \"schema:legalName\",\n    \"subscriptionId\": \"ion:subscriptionId\",\n    \"productName\": \"schema:name\",\n    \"vendor\": \"schema:manufacturer\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"subscriptionStatus\": \"ion:subscriptionStatus\",\n    \"autoRenew\": \"ion:autoRenew\",\n    \"renewalDate\": {\n      \"@id\": \"ion:renewalDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"orderId\": \"schema:orderNumber\",\n    \"sku\": \"schema:sku\",\n    \"currency\": \"schema:priceCurrency\",\n    \"totalAmount\": \"schema:price\",\n    \"email\": \"schema:email\",\n    \"country\": \"schema:addressCountry\",\n    \"createdAt\"\
  : {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/synnex/refs/heads/main/json-ld/synnex-context.jsonld
tags:
- Technology Distribution
- IT Distribution
- Cloud Marketplace
- Fortune 100
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
