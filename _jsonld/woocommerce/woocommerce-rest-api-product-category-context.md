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
class_count: 3
classes:
- ProductCategoryInput
- name
- description
context_file: json-ld/woocommerce-rest-api-product-category-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-category-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Product Category from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Product Category Context
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
  name: slug
  type: string
- container: ''
  name: parent
  type: integer
- container: ''
  name: display
  type: string
property_count: 3
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-product-category-context
source_filename: woocommerce-rest-api-product-category-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProductCategoryInput\": \"woo:ProductCategoryInput\",\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent\": {\n      \"@id\": \"woo:parent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"display\": {\n      \"@id\": \"woo:display\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-category-context.jsonld
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
