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
- WooCommerce Product
- name
- dateCreated
- dateModified
- description
context_file: json-ld/woocommerce-product-schema.json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-product-schema.json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Product Schema.Json from WooCommerce.
layout: jsonld
name: Woocommerce Product Schema.Json Context
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
  name: slug
  type: string
- container: ''
  name: permalink
  type: reference
- container: ''
  name: dateCreatedGmt
  type: dateTime
- container: ''
  name: dateModifiedGmt
  type: dateTime
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
  name: catalogVisibility
  type: string
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: sku
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
  name: dateOnSaleFrom
  type: dateTime
- container: ''
  name: dateOnSaleTo
  type: dateTime
- container: ''
  name: onSale
  type: boolean
- container: ''
  name: purchasable
  type: boolean
- container: ''
  name: totalSales
  type: integer
- container: ''
  name: virtual
  type: boolean
- container: ''
  name: downloadable
  type: boolean
- container: set
  name: downloads
  type: string
- container: ''
  name: downloadLimit
  type: integer
- container: ''
  name: downloadExpiry
  type: integer
- container: ''
  name: externalUrl
  type: reference
- container: ''
  name: buttonText
  type: string
- container: ''
  name: taxStatus
  type: string
- container: ''
  name: taxClass
  type: string
- container: ''
  name: manageStock
  type: boolean
- container: ''
  name: stockQuantity
  type: integer
- container: ''
  name: backorders
  type: string
- container: ''
  name: backordersAllowed
  type: boolean
- container: ''
  name: backordered
  type: boolean
- container: ''
  name: lowStockAmount
  type: integer
- container: ''
  name: soldIndividually
  type: boolean
- container: ''
  name: weight
  type: string
- container: ''
  name: dimensions
  type: string
- container: ''
  name: shippingRequired
  type: boolean
- container: ''
  name: shippingTaxable
  type: boolean
- container: ''
  name: shippingClass
  type: string
- container: ''
  name: shippingClassId
  type: integer
- container: ''
  name: reviewsAllowed
  type: boolean
- container: ''
  name: averageRating
  type: string
- container: ''
  name: ratingCount
  type: integer
- container: set
  name: upsellIds
  type: integer
- container: set
  name: crossSellIds
  type: integer
- container: ''
  name: parentId
  type: integer
- container: ''
  name: purchaseNote
  type: string
- container: set
  name: categories
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: images
  type: string
- container: set
  name: attributes
  type: string
- container: set
  name: defaultAttributes
  type: ''
- container: set
  name: variations
  type: integer
- container: set
  name: groupedProducts
  type: integer
- container: ''
  name: menuOrder
  type: integer
- container: set
  name: metaData
  type: string
property_count: 57
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-product-schema.json-context
source_filename: woocommerce-product-schema.json-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WooCommerce Product\": \"woo:WooCommerce Product\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permalink\": {\n      \"@id\": \"woo:permalink\",\n      \"@type\": \"@id\"\n    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateCreatedGmt\": {\n      \"@id\": \"woo:date_created_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateModified\": \"schema:dateModified\",\n    \"dateModifiedGmt\": {\n      \"@id\": \"woo:date_modified_gmt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n      \"@id\": \"woo:type\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featured\": {\n      \"@id\": \"woo:featured\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"catalogVisibility\": {\n      \"@id\": \"woo:catalog_visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"shortDescription\": {\n      \"@id\": \"woo:short_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOnSaleFrom\": {\n      \"@id\": \"woo:date_on_sale_from\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dateOnSaleTo\": {\n      \"\
  @id\": \"woo:date_on_sale_to\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"onSale\": {\n      \"@id\": \"woo:on_sale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"purchasable\": {\n      \"@id\": \"woo:purchasable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalSales\": {\n      \"@id\": \"woo:total_sales\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"virtual\": {\n      \"@id\": \"woo:virtual\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"downloadable\": {\n      \"@id\": \"woo:downloadable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"downloads\": {\n      \"@id\": \"woo:downloads\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadLimit\": {\n      \"@id\": \"woo:download_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"downloadExpiry\": {\n      \"@id\": \"woo:download_expiry\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"externalUrl\": {\n      \"@id\": \"woo:external_url\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"buttonText\": {\n      \"@id\": \"woo:button_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxStatus\": {\n      \"@id\": \"woo:tax_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxClass\": {\n      \"@id\": \"woo:tax_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manageStock\": {\n      \"@id\": \"woo:manage_stock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stockQuantity\": {\n      \"@id\": \"woo:stock_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"backorders\": {\n      \"@id\": \"woo:backorders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backordersAllowed\": {\n      \"@id\": \"woo:backorders_allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"backordered\": {\n      \"@id\": \"woo:backordered\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lowStockAmount\": {\n      \"@id\": \"woo:low_stock_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"soldIndividually\": {\n      \"@id\"\
  : \"woo:sold_individually\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"weight\": {\n      \"@id\": \"woo:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"woo:dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingRequired\": {\n      \"@id\": \"woo:shipping_required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shippingTaxable\": {\n      \"@id\": \"woo:shipping_taxable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shippingClass\": {\n      \"@id\": \"woo:shipping_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingClassId\": {\n      \"@id\": \"woo:shipping_class_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reviewsAllowed\": {\n      \"@id\": \"woo:reviews_allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"averageRating\": {\n      \"@id\": \"woo:average_rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ratingCount\": {\n      \"@id\": \"woo:rating_count\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"upsellIds\": {\n      \"@id\": \"woo:upsell_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"crossSellIds\": {\n      \"@id\": \"woo:cross_sell_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentId\": {\n      \"@id\": \"woo:parent_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"purchaseNote\": {\n      \"@id\": \"woo:purchase_note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\": \"woo:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"woo:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"woo:images\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"woo:attributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"defaultAttributes\": {\n      \"@id\": \"woo:default_attributes\",\n      \"@container\": \"@set\"\n    },\n    \"variations\": {\n      \"@id\": \"woo:variations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"groupedProducts\": {\n      \"@id\": \"woo:grouped_products\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"menuOrder\": {\n      \"@id\": \"woo:menu_order\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-product-schema.json-context.jsonld
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
