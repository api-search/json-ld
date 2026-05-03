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
- CustomerDownload
- name
- CustomerInput
- email
context_file: json-ld/woocommerce-rest-api-customer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-customer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Customer from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Customer Context
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
  name: downloadId
  type: string
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: productId
  type: integer
- container: ''
  name: productName
  type: string
- container: ''
  name: downloadName
  type: string
- container: ''
  name: orderId
  type: integer
- container: ''
  name: orderKey
  type: string
- container: ''
  name: downloadsRemaining
  type: string
- container: ''
  name: accessExpires
  type: dateTime
- container: ''
  name: file
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: billing
  type: reference
- container: ''
  name: company
  type: string
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
- container: ''
  name: phone
  type: string
- container: ''
  name: shipping
  type: reference
- container: set
  name: metaData
  type: ''
property_count: 25
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-customer-context
source_filename: woocommerce-rest-api-customer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomerDownload\": \"woo:CustomerDownload\",\n    \"downloadId\": {\n      \"@id\": \"woo:download_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"woo:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"productId\": {\n      \"@id\": \"woo:product_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"productName\": {\n      \"@id\": \"woo:product_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadName\": {\n      \"@id\": \"woo:download_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"woo:order_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"orderKey\": {\n      \"@id\": \"woo:order_key\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"downloadsRemaining\": {\n      \"@id\": \"woo:downloads_remaining\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessExpires\": {\n      \"@id\": \"woo:access_expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"file\": {\n      \"@id\": \"woo:file\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"CustomerInput\": \"woo:CustomerInput\",\n    \"email\": \"schema:email\",\n    \"firstName\": {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"woo:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"woo:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"woo:billing\",\n      \"@type\": \"@id\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipping\": {\n      \"@id\": \"woo:shipping\",\n      \"@type\": \"@id\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-customer-context.jsonld
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
