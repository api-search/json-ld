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
- CartItem
- name
- CartTotals
context_file: json-ld/woocommerce-store-api-cart-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-cart-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Cart from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Cart Context
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
  name: key
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: quantity
  type: integer
- container: ''
  name: variationId
  type: integer
- container: set
  name: itemData
  type: ''
- container: ''
  name: prices
  type: reference
- container: ''
  name: price
  type: string
- container: ''
  name: regularPrice
  type: string
- container: ''
  name: salePrice
  type: string
- container: ''
  name: priceRange
  type: reference
- container: ''
  name: minAmount
  type: string
- container: ''
  name: maxAmount
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: currencySymbol
  type: string
- container: ''
  name: currencyDecimalSeparator
  type: string
- container: ''
  name: currencyThousandSeparator
  type: string
- container: ''
  name: currencyPrefix
  type: string
- container: ''
  name: currencySuffix
  type: string
- container: ''
  name: shortDescription
  type: string
- container: set
  name: images
  type: ''
- container: ''
  name: lowStockRemaining
  type: integer
- container: ''
  name: soldIndividually
  type: boolean
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
property_count: 33
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-cart-context
source_filename: woocommerce-store-api-cart-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CartItem\": \"woo:CartItem\",\n    \"key\": {\n      \"@id\": \"woo:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quantity\": {\n      \"@id\": \"woo:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variationId\": {\n      \"@id\": \"woo:variation_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"itemData\": {\n      \"@id\": \"woo:item_data\",\n      \"@container\": \"@set\"\n    },\n    \"prices\": {\n      \"@id\": \"woo:prices\",\n      \"@type\": \"@id\"\n    },\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceRange\": {\n      \"@id\": \"woo:price_range\",\n      \"@type\": \"@id\"\n    },\n    \"minAmount\": {\n      \"@id\": \"woo:min_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAmount\": {\n      \"@id\": \"woo:max_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"woo:currency_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencySymbol\": {\n      \"@id\": \"woo:currency_symbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyDecimalSeparator\": {\n      \"@id\": \"woo:currency_decimal_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyThousandSeparator\": {\n      \"@id\": \"woo:currency_thousand_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyPrefix\": {\n      \"@id\": \"woo:currency_prefix\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"currencySuffix\": {\n      \"@id\": \"woo:currency_suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"shortDescription\": {\n      \"@id\": \"woo:short_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"woo:images\",\n      \"@container\": \"@set\"\n    },\n    \"lowStockRemaining\": {\n      \"@id\": \"woo:low_stock_remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"soldIndividually\": {\n      \"@id\": \"woo:sold_individually\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CartTotals\": \"woo:CartTotals\",\n    \"totalItems\": {\n      \"@id\": \"woo:total_items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalItemsTax\": {\n      \"@id\": \"woo:total_items_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalFees\": {\n      \"@id\": \"woo:total_fees\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalFeesTax\": {\n      \"@id\": \"woo:total_fees_tax\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"totalDiscount\": {\n      \"@id\": \"woo:total_discount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalDiscountTax\": {\n      \"@id\": \"woo:total_discount_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalShipping\": {\n      \"@id\": \"woo:total_shipping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalShippingTax\": {\n      \"@id\": \"woo:total_shipping_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalPrice\": {\n      \"@id\": \"woo:total_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTax\": {\n      \"@id\": \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxLines\": {\n      \"@id\": \"woo:tax_lines\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-cart-context.jsonld
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
