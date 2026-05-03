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
class_count: 5
classes:
- OrderInput
- email
- OrderNote
- dateCreated
- OrderRefund
context_file: json-ld/woocommerce-rest-api-order-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Order from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Order Context
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
  name: customerId
  type: integer
- container: ''
  name: customerNote
  type: boolean
- container: ''
  name: billing
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
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
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: paymentMethodTitle
  type: string
- container: set
  name: lineItems
  type: ''
- container: set
  name: metaData
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: note
  type: string
- container: ''
  name: addedByUser
  type: boolean
- container: ''
  name: amount
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: refundedBy
  type: integer
property_count: 25
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-order-context
source_filename: woocommerce-rest-api-order-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OrderInput\": \"woo:OrderInput\",\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"woo:customer_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerNote\": {\n      \"@id\": \"woo:customer_note\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"billing\": {\n      \"@id\": \"woo:billing\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\": {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"\
  @id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipping\": {\n      \"@id\": \"woo:shipping\",\n      \"@type\": \"@id\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"woo:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodTitle\": {\n      \"@id\": \"woo:payment_method_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"\
  @id\": \"woo:line_items\",\n      \"@container\": \"@set\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    },\n    \"OrderNote\": \"woo:OrderNote\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"note\": {\n      \"@id\": \"woo:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addedByUser\": {\n      \"@id\": \"woo:added_by_user\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"OrderRefund\": \"woo:OrderRefund\",\n    \"amount\": {\n      \"@id\": \"woo:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"woo:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundedBy\": {\n      \"@id\": \"woo:refunded_by\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-order-context.jsonld
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
