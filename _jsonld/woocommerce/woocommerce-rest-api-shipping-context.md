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
- ShippingMethod
- ShippingZone
- name
context_file: json-ld/woocommerce-rest-api-shipping-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-shipping-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Shipping from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Shipping Context
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
  name: instanceId
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: order
  type: integer
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: methodId
  type: string
- container: ''
  name: methodTitle
  type: string
- container: ''
  name: methodDescription
  type: string
property_count: 8
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-shipping-context
source_filename: woocommerce-rest-api-shipping-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ShippingMethod\": \"woo:ShippingMethod\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instanceId\": {\n      \"@id\": \"woo:instance_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"woo:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"woo:order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"woo:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"methodId\": {\n      \"@id\": \"woo:method_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"methodTitle\": {\n      \"@id\": \"woo:method_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"methodDescription\": {\n    \
  \  \"@id\": \"woo:method_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShippingZone\": \"woo:ShippingZone\",\n    \"name\": \"schema:name\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-shipping-context.jsonld
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
