---
api_specs:
- filename: woocommerce-rest-api-openapi.yml
  format: yaml
  label: WooCommerce REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-rest-api-openapi.yml
- filename: woocommerce-store-api-openapi.yml
  format: yaml
  label: WooCommerce Store API
  slug: store-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-store-api-openapi.yml
- filename: woocommerce-webhooks-asyncapi.yml
  format: yaml
  label: WooCommerce Webhook Events
  slug: webhook-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/asyncapi/woocommerce-webhooks-asyncapi.yml
class_count: 2
classes:
- CouponInput
- description
context_file: json-ld/woocommerce-rest-api-coupon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-coupon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Coupon from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Coupon Context
namespaces:
- prefix: woo
  uri: https://woocommerce.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: discountType
  type: string
- container: ''
  name: dateExpires
  type: dateTime
- container: ''
  name: individualUse
  type: boolean
- container: set
  name: productIds
  type: integer
- container: set
  name: excludedProductIds
  type: integer
- container: ''
  name: usageLimit
  type: integer
- container: ''
  name: usageLimitPerUser
  type: integer
- container: ''
  name: minimumAmount
  type: string
- container: ''
  name: maximumAmount
  type: string
- container: set
  name: metaData
  type: ''
property_count: 12
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-coupon-context
source_filename: woocommerce-rest-api-coupon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CouponInput\": \"woo:CouponInput\",\n    \"code\": {\n      \"@id\": \"woo:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"woo:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discountType\": {\n      \"@id\": \"woo:discount_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"dateExpires\": {\n      \"@id\": \"woo:date_expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"individualUse\": {\n      \"@id\": \"woo:individual_use\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"productIds\": {\n      \"@id\": \"woo:product_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"excludedProductIds\"\
  : {\n      \"@id\": \"woo:excluded_product_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usageLimit\": {\n      \"@id\": \"woo:usage_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usageLimitPerUser\": {\n      \"@id\": \"woo:usage_limit_per_user\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minimumAmount\": {\n      \"@id\": \"woo:minimum_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumAmount\": {\n      \"@id\": \"woo:maximum_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-coupon-context.jsonld
tags:
- eCommerce
- Open Source
- Orders
- Products
- WordPress
- JSON-LD
- Linked Data
- Semantic Web
---
