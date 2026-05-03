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
- AddCartItemInput
context_file: json-ld/woocommerce-store-api-add-cart-item-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-add-cart-item-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Add Cart Item from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Add Cart Item Context
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
  name: quantity
  type: integer
- container: ''
  name: variationId
  type: integer
- container: set
  name: variation
  type: ''
- container: set
  name: itemData
  type: ''
property_count: 5
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-add-cart-item-context
source_filename: woocommerce-store-api-add-cart-item-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddCartItemInput\": \"woo:AddCartItemInput\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quantity\": {\n      \"@id\": \"woo:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variationId\": {\n      \"@id\": \"woo:variation_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variation\": {\n      \"@id\": \"woo:variation\",\n      \"@container\": \"@set\"\n    },\n    \"itemData\": {\n      \"@id\": \"woo:item_data\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-add-cart-item-context.jsonld
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
