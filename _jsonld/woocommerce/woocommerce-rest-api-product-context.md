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
- ProductAttribute
- name
- ProductCategory
- description
- ProductImage
- ProductInput
- ProductVariation
context_file: json-ld/woocommerce-rest-api-product-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api Product from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Product Context
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
  name: position
  type: integer
- container: ''
  name: visible
  type: boolean
- container: ''
  name: variation
  type: boolean
- container: set
  name: options
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: parent
  type: integer
- container: ''
  name: display
  type: string
- container: ''
  name: image
  type: reference
- container: ''
  name: src
  type: reference
- container: ''
  name: alt
  type: string
- container: ''
  name: menuOrder
  type: integer
- container: ''
  name: count
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: featured
  type: boolean
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: regularPrice
  type: string
- container: ''
  name: salePrice
  type: string
- container: ''
  name: virtual
  type: boolean
- container: ''
  name: downloadable
  type: boolean
- container: ''
  name: manageStock
  type: boolean
- container: ''
  name: stockQuantity
  type: integer
- container: ''
  name: stockStatus
  type: string
- container: ''
  name: weight
  type: string
- container: set
  name: categories
  type: ''
- container: set
  name: tags
  type: ''
- container: set
  name: images
  type: ''
- container: set
  name: attributes
  type: ''
- container: set
  name: metaData
  type: ''
- container: ''
  name: price
  type: string
- container: ''
  name: onSale
  type: boolean
property_count: 33
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-product-context
source_filename: woocommerce-rest-api-product-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProductAttribute\": \"woo:ProductAttribute\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"position\": {\n      \"@id\": \"woo:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"visible\": {\n      \"@id\": \"woo:visible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"variation\": {\n      \"@id\": \"woo:variation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"options\": {\n      \"@id\": \"woo:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductCategory\": \"woo:ProductCategory\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent\": {\n\
  \      \"@id\": \"woo:parent\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"display\": {\n      \"@id\": \"woo:display\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"woo:image\",\n      \"@type\": \"@id\"\n    },\n    \"src\": {\n      \"@id\": \"woo:src\",\n      \"@type\": \"@id\"\n    },\n    \"alt\": {\n      \"@id\": \"woo:alt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"menuOrder\": {\n      \"@id\": \"woo:menu_order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"count\": {\n      \"@id\": \"woo:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ProductImage\": \"woo:ProductImage\",\n    \"ProductInput\": \"woo:ProductInput\",\n    \"type\": {\n      \"@id\": \"woo:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featured\": {\n      \"@id\": \"woo:featured\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"shortDescription\": {\n      \"@id\": \"woo:short_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtual\": {\n      \"@id\": \"woo:virtual\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"downloadable\": {\n      \"@id\": \"woo:downloadable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"manageStock\": {\n      \"@id\": \"woo:manage_stock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stockQuantity\": {\n      \"@id\": \"woo:stock_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stockStatus\": {\n      \"@id\": \"woo:stock_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"woo:weight\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"categories\": {\n      \"@id\": \"woo:categories\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"woo:tags\",\n      \"@container\": \"@set\"\n    },\n    \"images\": {\n      \"@id\": \"woo:images\",\n      \"@container\": \"@set\"\n    },\n    \"attributes\": {\n      \"@id\": \"woo:attributes\",\n      \"@container\": \"@set\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    },\n    \"ProductVariation\": \"woo:ProductVariation\",\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onSale\": {\n      \"@id\": \"woo:on_sale\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-product-context.jsonld
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
