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
class_count: 10
classes:
- StoreAddress
- email
- StoreBrand
- name
- description
- StoreOrder
- dateCreated
- StoreProduct
- url
- StoreReview
context_file: json-ld/woocommerce-store-api-store-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-store-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Store Api Store from WooCommerce.
layout: jsonld
name: Woocommerce Store Api Store Context
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
  name: id
  type: integer
- container: ''
  name: slug
  type: string
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
  name: number
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: billing
  type: reference
- container: ''
  name: shipping
  type: reference
- container: set
  name: items
  type: ''
- container: ''
  name: parent
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: variation
  type: string
- container: ''
  name: permalink
  type: reference
- container: ''
  name: sku
  type: string
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: onSale
  type: boolean
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
  name: purchasable
  type: boolean
- container: set
  name: images
  type: ''
- container: set
  name: categories
  type: ''
- container: set
  name: tags
  type: ''
- container: set
  name: attributes
  type: ''
- container: ''
  name: averageRating
  type: string
- container: ''
  name: reviewCount
  type: integer
- container: ''
  name: isInStock
  type: boolean
- container: ''
  name: lowStockRemaining
  type: integer
- container: ''
  name: soldIndividually
  type: boolean
- container: ''
  name: addToCart
  type: reference
- container: ''
  name: text
  type: string
- container: ''
  name: productId
  type: integer
- container: ''
  name: reviewer
  type: string
- container: ''
  name: review
  type: string
- container: ''
  name: rating
  type: integer
- container: ''
  name: verified
  type: boolean
property_count: 61
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-store-api-store-context
source_filename: woocommerce-store-api-store-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoreAddress\": \"woo:StoreAddress\",\n    \"firstName\": {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoreBrand\": \"woo:StoreBrand\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"image\": {\n      \"@id\": \"woo:image\",\n      \"@type\": \"@id\"\n    },\n    \"src\": {\n      \"@id\": \"woo:src\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnail\": {\n      \"@id\": \"woo:thumbnail\",\n      \"@type\": \"@id\"\n    },\n    \"srcset\": {\n      \"@id\": \"woo:srcset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizes\": {\n      \"@id\": \"woo:sizes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alt\"\
  : {\n      \"@id\": \"woo:alt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoreOrder\": \"woo:StoreOrder\",\n    \"number\": {\n      \"@id\": \"woo:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"total\": {\n      \"@id\": \"woo:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"woo:billing\",\n      \"@type\": \"@id\"\n    },\n    \"shipping\": {\n      \"@id\": \"woo:shipping\",\n      \"@type\": \"@id\"\n    },\n    \"items\": {\n      \"@id\": \"woo:items\",\n      \"@container\": \"@set\"\n    },\n    \"StoreProduct\": \"woo:StoreProduct\",\n    \"parent\": {\n      \"@id\": \"woo:parent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"woo:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variation\": {\n      \"@id\": \"woo:variation\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"permalink\": {\n      \"@id\": \"woo:permalink\",\n      \"@type\": \"@id\"\n    },\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"woo:short_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onSale\": {\n      \"@id\": \"woo:on_sale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"prices\": {\n      \"@id\": \"woo:prices\",\n      \"@type\": \"@id\"\n    },\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceRange\": {\n      \"@id\": \"woo:price_range\",\n      \"@type\": \"@id\"\n    },\n    \"minAmount\": {\n      \"@id\": \"woo:min_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAmount\"\
  : {\n      \"@id\": \"woo:max_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"woo:currency_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencySymbol\": {\n      \"@id\": \"woo:currency_symbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyDecimalSeparator\": {\n      \"@id\": \"woo:currency_decimal_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyThousandSeparator\": {\n      \"@id\": \"woo:currency_thousand_separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyPrefix\": {\n      \"@id\": \"woo:currency_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencySuffix\": {\n      \"@id\": \"woo:currency_suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchasable\": {\n      \"@id\": \"woo:purchasable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"images\": {\n      \"@id\": \"woo:images\",\n      \"@container\": \"@set\"\n    },\n    \"categories\": {\n      \"\
  @id\": \"woo:categories\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"woo:tags\",\n      \"@container\": \"@set\"\n    },\n    \"attributes\": {\n      \"@id\": \"woo:attributes\",\n      \"@container\": \"@set\"\n    },\n    \"averageRating\": {\n      \"@id\": \"woo:average_rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewCount\": {\n      \"@id\": \"woo:review_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isInStock\": {\n      \"@id\": \"woo:is_in_stock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lowStockRemaining\": {\n      \"@id\": \"woo:low_stock_remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"soldIndividually\": {\n      \"@id\": \"woo:sold_individually\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"addToCart\": {\n      \"@id\": \"woo:add_to_cart\",\n      \"@type\": \"@id\"\n    },\n    \"text\": {\n      \"@id\": \"woo:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\
  ,\n    \"StoreReview\": \"woo:StoreReview\",\n    \"productId\": {\n      \"@id\": \"woo:product_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reviewer\": {\n      \"@id\": \"woo:reviewer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"review\": {\n      \"@id\": \"woo:review\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"woo:rating\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"verified\": {\n      \"@id\": \"woo:verified\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-store-api-store-context.jsonld
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
