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
- CheckoutInput
- email
- CheckoutOrder
context_file: json-ld/woocommerce-store-api-checkout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-checkout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Checkout from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Checkout Context
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
  name: billingAddress
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
  name: shippingAddress
  type: reference
- container: ''
  name: customerNote
  type: string
- container: ''
  name: createAccount
  type: boolean
- container: ''
  name: paymentMethod
  type: string
- container: set
  name: paymentData
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: orderKey
  type: string
- container: ''
  name: orderNumber
  type: string
- container: ''
  name: paymentResult
  type: reference
- container: ''
  name: paymentStatus
  type: string
- container: set
  name: paymentDetails
  type: ''
- container: ''
  name: redirectUrl
  type: reference
property_count: 24
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-checkout-context
source_filename: woocommerce-store-api-checkout-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckoutInput\": \"woo:CheckoutInput\",\n    \"billingAddress\": {\n      \"@id\": \"woo:billing_address\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\": {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"\
  @id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingAddress\": {\n      \"@id\": \"woo:shipping_address\",\n      \"@type\": \"@id\"\n    },\n    \"customerNote\": {\n      \"@id\": \"woo:customer_note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createAccount\": {\n      \"@id\": \"woo:create_account\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"woo:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentData\": {\n      \"@id\": \"woo:payment_data\",\n      \"@container\": \"@set\"\n    },\n    \"CheckoutOrder\": \"woo:CheckoutOrder\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n     \
  \ \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderKey\": {\n      \"@id\": \"woo:order_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderNumber\": {\n      \"@id\": \"woo:order_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentResult\": {\n      \"@id\": \"woo:payment_result\",\n      \"@type\": \"@id\"\n    },\n    \"paymentStatus\": {\n      \"@id\": \"woo:payment_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentDetails\": {\n      \"@id\": \"woo:payment_details\",\n      \"@container\": \"@set\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"woo:redirect_url\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-checkout-context.jsonld
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
