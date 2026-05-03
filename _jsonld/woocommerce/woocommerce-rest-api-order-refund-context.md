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
class_count: 1
classes:
- OrderRefundInput
context_file: json-ld/woocommerce-rest-api-order-refund-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-refund-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Order Refund from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Order Refund Context
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
  name: amount
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: refundedBy
  type: integer
- container: ''
  name: apiRefund
  type: boolean
- container: set
  name: lineItems
  type: ''
property_count: 5
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-order-refund-context
source_filename: woocommerce-rest-api-order-refund-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OrderRefundInput\": \"woo:OrderRefundInput\",\n    \"amount\": {\n      \"@id\": \"woo:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"woo:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundedBy\": {\n      \"@id\": \"woo:refunded_by\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"apiRefund\": {\n      \"@id\": \"woo:api_refund\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lineItems\": {\n      \"@id\": \"woo:line_items\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-refund-context.jsonld
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
