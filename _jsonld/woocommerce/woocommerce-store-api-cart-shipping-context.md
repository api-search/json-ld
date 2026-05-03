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
- CartShippingRate
- name
context_file: json-ld/woocommerce-store-api-cart-shipping-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-cart-shipping-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Cart Shipping from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Cart Shipping Context
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
  name: packageId
  type: integer
- container: ''
  name: destination
  type: reference
- container: ''
  name: address1
  type: string
- container: ''
  name: address2
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postcode
  type: string
- container: ''
  name: country
  type: string
- container: set
  name: items
  type: ''
- container: set
  name: shippingRates
  type: ''
property_count: 10
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-cart-shipping-context
source_filename: woocommerce-store-api-cart-shipping-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CartShippingRate\": \"woo:CartShippingRate\",\n    \"packageId\": {\n      \"@id\": \"woo:package_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"destination\": {\n      \"@id\": \"woo:destination\",\n      \"@type\": \"@id\"\n    },\n    \"address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"woo:items\",\n      \"@container\": \"@set\"\n    },\n    \"shippingRates\": {\n      \"@id\": \"woo:shipping_rates\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-cart-shipping-context.jsonld
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
