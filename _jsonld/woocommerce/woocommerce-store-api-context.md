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
- Cart
- email
- Checkout
context_file: json-ld/woocommerce-store-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Context
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
- container: set
  name: items
  type: ''
- container: set
  name: coupons
  type: ''
- container: set
  name: fees
  type: ''
- container: ''
  name: totals
  type: reference
- container: ''
  name: totalItems
  type: string
- container: ''
  name: totalItemsTax
  type: string
- container: ''
  name: totalFees
  type: string
- container: ''
  name: totalFeesTax
  type: string
- container: ''
  name: totalDiscount
  type: string
- container: ''
  name: totalDiscountTax
  type: string
- container: ''
  name: totalShipping
  type: string
- container: ''
  name: totalShippingTax
  type: string
- container: ''
  name: totalPrice
  type: string
- container: ''
  name: totalTax
  type: string
- container: set
  name: taxLines
  type: ''
- container: set
  name: shippingRates
  type: ''
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
  name: hasCalculatedShipping
  type: boolean
- container: ''
  name: needsPayment
  type: boolean
- container: ''
  name: needsShipping
  type: boolean
- container: ''
  name: itemsCount
  type: integer
- container: ''
  name: itemsWeight
  type: decimal
- container: set
  name: crossSells
  type: ''
- container: set
  name: errors
  type: ''
- container: ''
  name: orderId
  type: integer
- container: set
  name: paymentMethods
  type: ''
property_count: 37
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-context
source_filename: woocommerce-store-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Cart\": \"woo:Cart\",\n    \"items\": {\n      \"@id\": \"woo:items\",\n      \"@container\": \"@set\"\n    },\n    \"coupons\": {\n      \"@id\": \"woo:coupons\",\n      \"@container\": \"@set\"\n    },\n    \"fees\": {\n      \"@id\": \"woo:fees\",\n      \"@container\": \"@set\"\n    },\n    \"totals\": {\n      \"@id\": \"woo:totals\",\n      \"@type\": \"@id\"\n    },\n    \"totalItems\": {\n      \"@id\": \"woo:total_items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalItemsTax\": {\n      \"@id\": \"woo:total_items_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalFees\": {\n      \"@id\": \"woo:total_fees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalFeesTax\": {\n      \"@id\": \"woo:total_fees_tax\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"totalDiscount\": {\n      \"@id\": \"woo:total_discount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalDiscountTax\": {\n      \"@id\": \"woo:total_discount_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalShipping\": {\n      \"@id\": \"woo:total_shipping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalShippingTax\": {\n      \"@id\": \"woo:total_shipping_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalPrice\": {\n      \"@id\": \"woo:total_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTax\": {\n      \"@id\": \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxLines\": {\n      \"@id\": \"woo:tax_lines\",\n      \"@container\": \"@set\"\n    },\n    \"shippingRates\": {\n      \"@id\": \"woo:shipping_rates\",\n      \"@container\": \"@set\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"woo:billing_address\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\"\
  : {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingAddress\": {\n      \"@id\"\
  : \"woo:shipping_address\",\n      \"@type\": \"@id\"\n    },\n    \"hasCalculatedShipping\": {\n      \"@id\": \"woo:has_calculated_shipping\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"needsPayment\": {\n      \"@id\": \"woo:needs_payment\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"needsShipping\": {\n      \"@id\": \"woo:needs_shipping\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"itemsCount\": {\n      \"@id\": \"woo:items_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"itemsWeight\": {\n      \"@id\": \"woo:items_weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"crossSells\": {\n      \"@id\": \"woo:cross_sells\",\n      \"@container\": \"@set\"\n    },\n    \"errors\": {\n      \"@id\": \"woo:errors\",\n      \"@container\": \"@set\"\n    },\n    \"Checkout\": \"woo:Checkout\",\n    \"orderId\": {\n      \"@id\": \"woo:order_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"paymentMethods\": {\n      \"@id\": \"woo:payment_methods\",\n\
  \      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-context.jsonld
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
