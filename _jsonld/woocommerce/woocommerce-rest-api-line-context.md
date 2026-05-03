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
- LineItem
- name
context_file: json-ld/woocommerce-rest-api-line-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-line-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Line from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Line Context
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
  name: id
  type: integer
- container: ''
  name: productId
  type: integer
- container: ''
  name: variationId
  type: integer
- container: ''
  name: quantity
  type: integer
- container: ''
  name: taxClass
  type: string
- container: ''
  name: subtotal
  type: string
- container: ''
  name: subtotalTax
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: totalTax
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: price
  type: decimal
- container: set
  name: metaData
  type: ''
property_count: 12
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-line-context
source_filename: woocommerce-rest-api-line-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LineItem\": \"woo:LineItem\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"productId\": {\n      \"@id\": \"woo:product_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variationId\": {\n      \"@id\": \"woo:variation_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quantity\": {\n      \"@id\": \"woo:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taxClass\": {\n      \"@id\": \"woo:tax_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtotal\": {\n      \"@id\": \"woo:subtotal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subtotalTax\": {\n      \"@id\": \"woo:subtotal_tax\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"total\": {\n      \"@id\": \"woo:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTax\": {\n      \"@id\": \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-line-context.jsonld
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
