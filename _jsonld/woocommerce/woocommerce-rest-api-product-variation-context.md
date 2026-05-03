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
- ProductVariationInput
- name
context_file: json-ld/woocommerce-rest-api-product-variation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-variation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Product Variation from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Product Variation Context
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
  name: sku
  type: string
- container: ''
  name: regularPrice
  type: string
- container: ''
  name: salePrice
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: manageStock
  type: boolean
- container: ''
  name: stockQuantity
  type: integer
- container: ''
  name: stockStatus
  type: string
- container: ''
  name: image
  type: reference
- container: ''
  name: id
  type: integer
- container: ''
  name: src
  type: reference
- container: ''
  name: alt
  type: string
- container: set
  name: attributes
  type: ''
property_count: 12
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-product-variation-context
source_filename: woocommerce-rest-api-product-variation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProductVariationInput\": \"woo:ProductVariationInput\",\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manageStock\": {\n      \"@id\": \"woo:manage_stock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stockQuantity\": {\n      \"@id\": \"woo:stock_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stockStatus\": {\n      \"@id\": \"woo:stock_status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"image\": {\n      \"@id\": \"woo:image\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"src\": {\n      \"@id\": \"woo:src\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"alt\": {\n      \"@id\": \"woo:alt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"woo:attributes\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-variation-context.jsonld
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
