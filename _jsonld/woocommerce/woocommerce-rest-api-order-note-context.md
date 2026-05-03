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
- OrderNoteInput
context_file: json-ld/woocommerce-rest-api-order-note-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-note-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Order Note from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Order Note Context
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
  name: note
  type: string
- container: ''
  name: customerNote
  type: boolean
- container: ''
  name: addedByUser
  type: boolean
property_count: 3
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-order-note-context
source_filename: woocommerce-rest-api-order-note-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OrderNoteInput\": \"woo:OrderNoteInput\",\n    \"note\": {\n      \"@id\": \"woo:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerNote\": {\n      \"@id\": \"woo:customer_note\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"addedByUser\": {\n      \"@id\": \"woo:added_by_user\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-note-context.jsonld
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
