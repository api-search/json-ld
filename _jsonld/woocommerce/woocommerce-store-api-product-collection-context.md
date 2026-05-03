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
- ProductCollectionData
context_file: json-ld/woocommerce-store-api-product-collection-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-product-collection-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Product Collection from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Product Collection Context
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
  name: priceRange
  type: reference
- container: ''
  name: minPrice
  type: string
- container: ''
  name: maxPrice
  type: string
- container: set
  name: attributeCounts
  type: ''
- container: set
  name: ratingCounts
  type: ''
property_count: 5
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-product-collection-context
source_filename: woocommerce-store-api-product-collection-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProductCollectionData\": \"woo:ProductCollectionData\",\n    \"priceRange\": {\n      \"@id\": \"woo:price_range\",\n      \"@type\": \"@id\"\n    },\n    \"minPrice\": {\n      \"@id\": \"woo:min_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxPrice\": {\n      \"@id\": \"woo:max_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributeCounts\": {\n      \"@id\": \"woo:attribute_counts\",\n      \"@container\": \"@set\"\n    },\n    \"ratingCounts\": {\n      \"@id\": \"woo:rating_counts\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-product-collection-context.jsonld
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
