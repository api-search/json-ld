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
- SalesReport
context_file: json-ld/woocommerce-rest-api-sales-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-sales-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Sales from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Sales Context
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
  name: totalSales
  type: string
- container: ''
  name: netRevenue
  type: string
- container: ''
  name: averageSales
  type: string
- container: ''
  name: totalOrders
  type: integer
- container: ''
  name: totalItems
  type: integer
- container: ''
  name: totalTax
  type: string
- container: ''
  name: totalShipping
  type: string
- container: ''
  name: totalRefunds
  type: decimal
- container: ''
  name: totalDiscount
  type: decimal
- container: ''
  name: totalsGroupedBy
  type: string
- container: ''
  name: totals
  type: reference
property_count: 11
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-sales-context
source_filename: woocommerce-rest-api-sales-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SalesReport\": \"woo:SalesReport\",\n    \"totalSales\": {\n      \"@id\": \"woo:total_sales\",\n      \"@type\": \"xsd:string\"\n    },\n    \"netRevenue\": {\n      \"@id\": \"woo:net_revenue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"averageSales\": {\n      \"@id\": \"woo:average_sales\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalOrders\": {\n      \"@id\": \"woo:total_orders\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalItems\": {\n      \"@id\": \"woo:total_items\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalTax\": {\n      \"@id\": \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalShipping\": {\n      \"@id\": \"woo:total_shipping\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"totalRefunds\": {\n      \"@id\": \"woo:total_refunds\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalDiscount\": {\n      \"@id\": \"woo:total_discount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalsGroupedBy\": {\n      \"@id\": \"woo:totals_grouped_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totals\": {\n      \"@id\": \"woo:totals\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-sales-context.jsonld
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
