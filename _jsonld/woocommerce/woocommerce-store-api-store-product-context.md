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
class_count: 7
classes:
- StoreProductAttribute
- name
- StoreProductCategory
- description
- StoreProductImage
- StoreProductPrice
- StoreProductTag
context_file: json-ld/woocommerce-store-api-store-product-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-store-product-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Store Product from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Store Product Context
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
  name: taxonomy
  type: string
- container: ''
  name: hasArchives
  type: boolean
- container: ''
  name: order
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: slug
  type: string
- container: ''
  name: parent
  type: integer
- container: ''
  name: link
  type: reference
- container: ''
  name: image
  type: reference
- container: ''
  name: src
  type: reference
- container: ''
  name: thumbnail
  type: reference
- container: ''
  name: srcset
  type: string
- container: ''
  name: sizes
  type: string
- container: ''
  name: alt
  type: string
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
property_count: 26
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-store-product-context
source_filename: woocommerce-store-api-store-product-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoreProductAttribute\": \"woo:StoreProductAttribute\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"taxonomy\": {\n      \"@id\": \"woo:taxonomy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasArchives\": {\n      \"@id\": \"woo:has_archives\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"order\": {\n      \"@id\": \"woo:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"woo:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"StoreProductCategory\": \"woo:StoreProductCategory\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\"\
  ,\n    \"parent\": {\n      \"@id\": \"woo:parent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"link\": {\n      \"@id\": \"woo:link\",\n      \"@type\": \"@id\"\n    },\n    \"image\": {\n      \"@id\": \"woo:image\",\n      \"@type\": \"@id\"\n    },\n    \"src\": {\n      \"@id\": \"woo:src\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnail\": {\n      \"@id\": \"woo:thumbnail\",\n      \"@type\": \"@id\"\n    },\n    \"srcset\": {\n      \"@id\": \"woo:srcset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizes\": {\n      \"@id\": \"woo:sizes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alt\": {\n      \"@id\": \"woo:alt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoreProductImage\": \"woo:StoreProductImage\",\n    \"StoreProductPrice\": \"woo:StoreProductPrice\",\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceRange\": {\n      \"@id\": \"woo:price_range\",\n      \"@type\": \"@id\"\n    },\n    \"minAmount\": {\n      \"@id\": \"woo:min_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAmount\": {\n      \"@id\": \"woo:max_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"woo:currency_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencySymbol\": {\n      \"@id\": \"woo:currency_symbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyDecimalSeparator\": {\n      \"@id\": \"woo:currency_decimal_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyThousandSeparator\": {\n      \"@id\": \"woo:currency_thousand_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyPrefix\": {\n      \"@id\": \"woo:currency_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencySuffix\"\
  : {\n      \"@id\": \"woo:currency_suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoreProductTag\": \"woo:StoreProductTag\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-store-product-context.jsonld
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
