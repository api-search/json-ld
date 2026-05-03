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
- WebhookInput
- name
context_file: json-ld/woocommerce-rest-api-webhook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-webhook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Webhook from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Webhook Context
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
  name: status
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: deliveryUrl
  type: reference
- container: ''
  name: secret
  type: string
property_count: 4
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-webhook-context
source_filename: woocommerce-rest-api-webhook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WebhookInput\": \"woo:WebhookInput\",\n    \"name\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"woo:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryUrl\": {\n      \"@id\": \"woo:delivery_url\",\n      \"@type\": \"@id\"\n    },\n    \"secret\": {\n      \"@id\": \"woo:secret\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-webhook-context.jsonld
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
