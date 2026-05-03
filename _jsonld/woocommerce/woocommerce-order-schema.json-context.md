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
- WooCommerce Order
- version
- dateCreated
- dateModified
context_file: json-ld/woocommerce-order-schema.json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-order-schema.json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Order Schema.Json from WooCommerce.
layout: jsonld
name: Woocommerce Order Schema.Json Context
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
  name: parentId
  type: integer
- container: ''
  name: number
  type: string
- container: ''
  name: orderKey
  type: string
- container: ''
  name: createdVia
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: dateCreatedGmt
  type: dateTime
- container: ''
  name: dateModifiedGmt
  type: dateTime
- container: ''
  name: dateCompleted
  type: dateTime
- container: ''
  name: datePaid
  type: dateTime
- container: ''
  name: discountTotal
  type: string
- container: ''
  name: discountTax
  type: string
- container: ''
  name: shippingTotal
  type: string
- container: ''
  name: shippingTax
  type: string
- container: ''
  name: cartTax
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: totalTax
  type: string
- container: ''
  name: pricesIncludeTax
  type: boolean
- container: ''
  name: customerId
  type: integer
- container: ''
  name: customerIpAddress
  type: string
- container: ''
  name: customerUserAgent
  type: string
- container: ''
  name: customerNote
  type: string
- container: ''
  name: billing
  type: string
- container: ''
  name: shipping
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: paymentMethodTitle
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: paymentUrl
  type: reference
- container: set
  name: lineItems
  type: string
- container: set
  name: taxLines
  type: string
- container: set
  name: shippingLines
  type: string
- container: set
  name: feeLines
  type: string
- container: set
  name: couponLines
  type: string
- container: set
  name: refunds
  type: string
- container: set
  name: metaData
  type: string
property_count: 36
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-order-schema.json-context
source_filename: woocommerce-order-schema.json-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WooCommerce Order\": \"woo:WooCommerce Order\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentId\": {\n      \"@id\": \"woo:parent_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"number\": {\n      \"@id\": \"woo:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderKey\": {\n      \"@id\": \"woo:order_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdVia\": {\n      \"@id\": \"woo:created_via\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"woo:currency\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateCreatedGmt\": {\n      \"@id\": \"woo:date_created_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": \"schema:dateModified\",\n    \"dateModifiedGmt\": {\n      \"@id\": \"woo:date_modified_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateCompleted\": {\n      \"@id\": \"woo:date_completed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"datePaid\": {\n      \"@id\": \"woo:date_paid\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"discountTotal\": {\n      \"@id\": \"woo:discount_total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discountTax\": {\n      \"@id\": \"woo:discount_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingTotal\": {\n      \"@id\": \"woo:shipping_total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingTax\": {\n      \"@id\": \"woo:shipping_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cartTax\": {\n      \"@id\": \"woo:cart_tax\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"woo:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTax\": {\n      \"@id\": \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricesIncludeTax\": {\n      \"@id\": \"woo:prices_include_tax\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"customerId\": {\n      \"@id\": \"woo:customer_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerIpAddress\": {\n      \"@id\": \"woo:customer_ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerUserAgent\": {\n      \"@id\": \"woo:customer_user_agent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerNote\": {\n      \"@id\": \"woo:customer_note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"woo:billing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipping\": {\n      \"@id\": \"woo:shipping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n\
  \      \"@id\": \"woo:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodTitle\": {\n      \"@id\": \"woo:payment_method_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"woo:transaction_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentUrl\": {\n      \"@id\": \"woo:payment_url\",\n      \"@type\": \"@id\"\n    },\n    \"lineItems\": {\n      \"@id\": \"woo:line_items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxLines\": {\n      \"@id\": \"woo:tax_lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingLines\": {\n      \"@id\": \"woo:shipping_lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feeLines\": {\n      \"@id\": \"woo:fee_lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"couponLines\": {\n      \"@id\": \"woo:coupon_lines\",\n    \
  \  \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refunds\": {\n      \"@id\": \"woo:refunds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-order-schema.json-context.jsonld
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
