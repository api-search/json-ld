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
class_count: 11
classes:
- Address
- email
- Coupon
- description
- dateCreated
- dateModified
- Customer
- Order
- Product
- name
- Webhook
context_file: json-ld/woocommerce-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api Context
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
  name: code
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: discountType
  type: string
- container: ''
  name: dateExpires
  type: dateTime
- container: ''
  name: usageCount
  type: integer
- container: ''
  name: individualUse
  type: boolean
- container: set
  name: productIds
  type: integer
- container: set
  name: excludedProductIds
  type: integer
- container: ''
  name: usageLimit
  type: integer
- container: ''
  name: usageLimitPerUser
  type: integer
- container: ''
  name: minimumAmount
  type: string
- container: ''
  name: maximumAmount
  type: string
- container: set
  name: metaData
  type: ''
- container: ''
  name: role
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: billing
  type: reference
- container: ''
  name: shipping
  type: reference
- container: ''
  name: isPayingCustomer
  type: boolean
- container: ''
  name: ordersCount
  type: integer
- container: ''
  name: totalSpent
  type: string
- container: ''
  name: avatarUrl
  type: reference
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
  name: status
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: dateCompleted
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
  name: customerId
  type: integer
- container: ''
  name: customerNote
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
- container: set
  name: lineItems
  type: ''
- container: ''
  name: slug
  type: string
- container: ''
  name: permalink
  type: reference
- container: ''
  name: type
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
  name: price
  type: string
- container: ''
  name: regularPrice
  type: string
- container: ''
  name: salePrice
  type: string
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
- container: ''
  name: dimensions
  type: reference
- container: ''
  name: length
  type: string
- container: ''
  name: width
  type: string
- container: ''
  name: height
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
- container: ''
  name: topic
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: deliveryUrl
  type: reference
property_count: 81
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-context
source_filename: woocommerce-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"woo:Address\",\n    \"firstName\": {\n      \"@id\": \"woo:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"woo:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"woo:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"@id\": \"woo:address_1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"woo:address_2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"woo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"woo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postcode\": {\n      \"@id\": \"woo:postcode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"woo:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"woo:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Coupon\": \"woo:Coupon\",\n    \"id\": {\n      \"@id\": \"woo:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"woo:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"woo:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discountType\": {\n      \"@id\": \"woo:discount_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"dateExpires\": {\n      \"@id\": \"woo:date_expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"usageCount\": {\n      \"@id\": \"woo:usage_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"individualUse\": {\n      \"@id\": \"woo:individual_use\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"productIds\": {\n      \"@id\": \"woo:product_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"excludedProductIds\": {\n      \"@id\": \"woo:excluded_product_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usageLimit\": {\n      \"@id\": \"woo:usage_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usageLimitPerUser\": {\n      \"@id\": \"woo:usage_limit_per_user\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minimumAmount\": {\n      \"@id\": \"woo:minimum_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumAmount\": {\n      \"@id\": \"woo:maximum_amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"metaData\": {\n      \"@id\": \"woo:meta_data\",\n      \"@container\": \"@set\"\n    },\n    \"Customer\": \"woo:Customer\",\n    \"role\": {\n      \"\
  @id\": \"woo:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"woo:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"woo:billing\",\n      \"@type\": \"@id\"\n    },\n    \"shipping\": {\n      \"@id\": \"woo:shipping\",\n      \"@type\": \"@id\"\n    },\n    \"isPayingCustomer\": {\n      \"@id\": \"woo:is_paying_customer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ordersCount\": {\n      \"@id\": \"woo:orders_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalSpent\": {\n      \"@id\": \"woo:total_spent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatarUrl\": {\n      \"@id\": \"woo:avatar_url\",\n      \"@type\": \"@id\"\n    },\n    \"Order\": \"woo:Order\",\n    \"parentId\": {\n      \"@id\": \"woo:parent_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"number\": {\n      \"@id\": \"woo:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderKey\": {\n      \"@id\"\
  : \"woo:order_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"woo:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"woo:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCompleted\": {\n      \"@id\": \"woo:date_completed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"discountTotal\": {\n      \"@id\": \"woo:discount_total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discountTax\": {\n      \"@id\": \"woo:discount_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingTotal\": {\n      \"@id\": \"woo:shipping_total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingTax\": {\n      \"@id\": \"woo:shipping_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cartTax\": {\n      \"@id\": \"woo:cart_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"woo:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTax\": {\n      \"@id\"\
  : \"woo:total_tax\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"woo:customer_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerNote\": {\n      \"@id\": \"woo:customer_note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"woo:payment_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodTitle\": {\n      \"@id\": \"woo:payment_method_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"woo:transaction_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItems\": {\n      \"@id\": \"woo:line_items\",\n      \"@container\": \"@set\"\n    },\n    \"Product\": \"woo:Product\",\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"woo:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permalink\": {\n      \"@id\": \"woo:permalink\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"woo:type\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"featured\": {\n      \"@id\": \"woo:featured\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"woo:short_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"woo:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"woo:price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regularPrice\": {\n      \"@id\": \"woo:regular_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salePrice\": {\n      \"@id\": \"woo:sale_price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onSale\": {\n      \"@id\": \"woo:on_sale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"purchasable\": {\n      \"@id\": \"woo:purchasable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"totalSales\": {\n      \"@id\": \"woo:total_sales\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"virtual\": {\n      \"@id\": \"woo:virtual\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"downloadable\": {\n      \"@id\": \"woo:downloadable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"manageStock\": {\n      \"@id\": \"woo:manage_stock\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stockQuantity\": {\n      \"@id\": \"woo:stock_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stockStatus\": {\n      \"@id\": \"woo:stock_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"woo:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"woo:dimensions\",\n      \"@type\": \"@id\"\n    },\n    \"length\": {\n      \"@id\": \"woo:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"woo:width\",\n      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"woo:height\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\": \"woo:categories\",\n      \"@container\": \"@set\"\n    },\n    \"tags\"\
  : {\n      \"@id\": \"woo:tags\",\n      \"@container\": \"@set\"\n    },\n    \"images\": {\n      \"@id\": \"woo:images\",\n      \"@container\": \"@set\"\n    },\n    \"attributes\": {\n      \"@id\": \"woo:attributes\",\n      \"@container\": \"@set\"\n    },\n    \"Webhook\": \"woo:Webhook\",\n    \"topic\": {\n      \"@id\": \"woo:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"woo:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"woo:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryUrl\": {\n      \"@id\": \"woo:delivery_url\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-context.jsonld
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
