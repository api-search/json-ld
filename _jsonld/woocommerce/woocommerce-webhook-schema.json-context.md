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
class_count: 4
classes:
- WooCommerce Webhook
- name
- dateCreated
- dateModified
context_file: json-ld/woocommerce-webhook-schema.json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-webhook-schema.json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Webhook Schema.Json from WooCommerce.
layout: jsonld
name: Woocommerce Webhook Schema.Json Context
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
  name: status
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: event
  type: string
- container: set
  name: hooks
  type: string
- container: ''
  name: deliveryUrl
  type: reference
- container: ''
  name: secret
  type: string
- container: ''
  name: dateCreatedGmt
  type: dateTime
- container: ''
  name: dateModifiedGmt
  type: dateTime
property_count: 10
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-webhook-schema.json-context
source_filename: woocommerce-webhook-schema.json-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WooCommerce Webhook\": \"woo:WooCommerce Webhook\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"woo:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"woo:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"woo:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hooks\": {\n      \"@id\": \"woo:hooks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryUrl\": {\n      \"@id\": \"woo:delivery_url\",\n      \"@type\": \"\
  @id\"\n    },\n    \"secret\": {\n      \"@id\": \"woo:secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateCreatedGmt\": {\n      \"@id\": \"woo:date_created_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": \"schema:dateModified\",\n    \"dateModifiedGmt\": {\n      \"@id\": \"woo:date_modified_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-webhook-schema.json-context.jsonld
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
