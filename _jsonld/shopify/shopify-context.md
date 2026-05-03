---
api_specs:
- filename: shopify-api-openapi.yml
  format: yaml
  label: Shopify  API
  slug: shopify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/openapi/shopify-api-openapi.yml
- filename: shopify-ajax-api-openapi.yml
  format: yaml
  label: Shopify Ajax API
  slug: ajax-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/openapi/shopify-ajax-api-openapi.yml
- filename: shopify-webhooks-api-openapi.yml
  format: yaml
  label: Shopify Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/openapi/shopify-webhooks-api-openapi.yml
- filename: shopify-multipass-api-openapi.yml
  format: yaml
  label: Shopify Multipass API
  slug: multipass-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/openapi/shopify-multipass-api-openapi.yml
class_count: 75
classes:
- Product
- ProductVariant
- ProductOption
- ProductImage
- Collection
- Customer
- Order
- LineItem
- Fulfillment
- FulfillmentOrder
- InventoryItem
- InventoryLevel
- Location
- Address
- Shop
- Webhook
- Refund
- ShippingLine
- Cart
- CartItem
- id
- title
- name
- body_html
- description
- handle
- url
- src
- alt
- vendor
- product_type
- tags
- status
- currency
- sku
- barcode
- weight_unit
- email
- phone
- first_name
- last_name
- company
- address1
- address2
- city
- province
- province_code
- country
- country_code
- zip
- order_number
- financial_status
- fulfillment_status
- billing_address
- shipping_address
- line_items
- customer
- tracking_company
- tracking_number
- tracking_url
- image
- featured_image
- default_address
- domain
- myshopify_domain
- shop_owner
- timezone
- iana_timezone
- plan_name
- money_format
- primary_locale
- topic
- address
- format
- api_version
context_file: json-ld/shopify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/json-ld/shopify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shopify from Shopify.
layout: jsonld
name: Shopify Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shopify
  uri: https://shopify.dev/schemas/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: dc
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: price
  type: decimal
- container: ''
  name: compare_at_price
  type: decimal
- container: ''
  name: total_price
  type: decimal
- container: ''
  name: subtotal_price
  type: decimal
- container: ''
  name: total_tax
  type: decimal
- container: ''
  name: total_discounts
  type: decimal
- container: ''
  name: grams
  type: integer
- container: ''
  name: weight
  type: decimal
- container: ''
  name: inventory_quantity
  type: integer
- container: ''
  name: requires_shipping
  type: boolean
- container: ''
  name: taxable
  type: boolean
- container: ''
  name: confirmed
  type: boolean
- container: ''
  name: quantity
  type: integer
- container: ''
  name: published_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: closed_at
  type: dateTime
- container: ''
  name: cancelled_at
  type: dateTime
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: position
  type: integer
- container: list
  name: variants
  type: ''
- container: list
  name: options
  type: ''
- container: list
  name: images
  type: ''
- container: list
  name: addresses
  type: ''
- container: list
  name: shipping_lines
  type: ''
- container: list
  name: fulfillments
  type: ''
- container: ''
  name: active
  type: boolean
- container: ''
  name: available
  type: boolean
property_count: 29
provider_name: Shopify
provider_slug: shopify
slug: shopify-context
source_filename: shopify-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shopify\": \"https://shopify.dev/schemas/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"dc\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"ProductVariant\": \"schema:ProductModel\",\n    \"ProductOption\": \"shopify:ProductOption\",\n    \"ProductImage\": \"schema:ImageObject\",\n    \"Collection\": \"schema:CollectionPage\",\n    \"Customer\": \"schema:Person\",\n    \"Order\": \"schema:Order\",\n    \"LineItem\": \"schema:OrderItem\",\n    \"Fulfillment\": \"shopify:Fulfillment\",\n    \"FulfillmentOrder\": \"shopify:FulfillmentOrder\",\n    \"InventoryItem\": \"shopify:InventoryItem\",\n    \"InventoryLevel\": \"shopify:InventoryLevel\",\n    \"Location\": \"schema:Place\",\n    \"Address\": \"schema:PostalAddress\",\n    \"Shop\": \"schema:Store\",\n    \"Webhook\": \"shopify:Webhook\"\
  ,\n    \"Refund\": \"shopify:Refund\",\n    \"ShippingLine\": \"schema:ParcelDelivery\",\n    \"Cart\": \"schema:Order\",\n    \"CartItem\": \"schema:OrderItem\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"body_html\": \"schema:description\",\n    \"description\": \"schema:description\",\n    \"handle\": \"schema:identifier\",\n    \"url\": \"schema:url\",\n    \"src\": \"schema:contentUrl\",\n    \"alt\": \"schema:caption\",\n\n    \"vendor\": \"schema:brand\",\n    \"product_type\": \"schema:category\",\n    \"tags\": \"schema:keywords\",\n    \"status\": \"schema:creativeWorkStatus\",\n\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"compare_at_price\": {\n      \"@id\": \"gr:hasPriceSpecification\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"total_price\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"subtotal_price\": {\n      \"@id\": \"shopify:subtotalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total_tax\": {\n      \"@id\": \"shopify:totalTax\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"total_discounts\": {\n      \"@id\": \"schema:discount\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"sku\": \"schema:sku\",\n    \"barcode\": \"schema:gtin\",\n    \"grams\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"weight_unit\": \"schema:unitCode\",\n    \"inventory_quantity\": {\n      \"@id\": \"schema:inventoryLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requires_shipping\": {\n      \"@id\": \"shopify:requiresShipping\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"taxable\": {\n      \"@id\": \"shopify:taxable\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"email\": \"schema:email\",\n\
  \    \"phone\": \"schema:telephone\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"company\": \"schema:worksFor\",\n    \"address1\": \"schema:streetAddress\",\n    \"address2\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"province\": \"schema:addressRegion\",\n    \"province_code\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"country_code\": \"schema:addressCountry\",\n    \"zip\": \"schema:postalCode\",\n\n    \"order_number\": \"schema:orderNumber\",\n    \"financial_status\": \"schema:paymentStatus\",\n    \"fulfillment_status\": \"schema:orderStatus\",\n    \"confirmed\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"billing_address\": \"schema:billingAddress\",\n    \"shipping_address\": \"schema:deliveryAddress\",\n    \"line_items\": \"schema:orderedItem\",\n    \"quantity\": {\n      \"@id\": \"schema:orderQuantity\",\n\
  \      \"@type\": \"xsd:integer\"\n    },\n    \"customer\": \"schema:customer\",\n\n    \"tracking_company\": \"schema:deliveryAddress\",\n    \"tracking_number\": \"schema:trackingNumber\",\n    \"tracking_url\": \"schema:trackingUrl\",\n\n    \"published_at\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_at\": {\n      \"@id\": \"dc:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"dc:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"closed_at\": {\n      \"@id\": \"shopify:closedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"cancelled_at\": {\n      \"@id\": \"shopify:cancelledAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"width\": {\n      \"@id\": \"schema:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"schema:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"position\": {\n      \"@id\": \"schema:position\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"variants\": {\n      \"@id\": \"schema:hasVariant\",\n      \"@container\": \"@list\"\n    },\n    \"options\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@container\": \"@list\"\n    },\n    \"images\": {\n      \"@id\": \"schema:image\",\n      \"@container\": \"@list\"\n    },\n    \"image\": \"schema:image\",\n    \"featured_image\": \"schema:image\",\n    \"addresses\": {\n      \"@id\": \"schema:address\",\n      \"@container\": \"@list\"\n    },\n    \"default_address\": \"schema:address\",\n    \"shipping_lines\": {\n      \"@id\": \"schema:deliveryMethod\",\n      \"@container\": \"@list\"\n    },\n    \"fulfillments\": {\n      \"@id\": \"schema:orderDelivery\",\n      \"@container\": \"@list\"\n    },\n\n    \"domain\": \"schema:url\",\n    \"myshopify_domain\": \"schema:url\",\n    \"shop_owner\": \"schema:founder\",\n    \"timezone\": \"shopify:timezone\",\n    \"iana_timezone\": \"shopify:ianaTimezone\",\n\
  \    \"plan_name\": \"shopify:planName\",\n    \"money_format\": \"shopify:moneyFormat\",\n    \"primary_locale\": \"schema:inLanguage\",\n\n    \"active\": {\n      \"@id\": \"shopify:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"available\": {\n      \"@id\": \"schema:availability\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"topic\": \"shopify:webhookTopic\",\n    \"address\": \"shopify:callbackUrl\",\n    \"format\": \"schema:encodingFormat\",\n    \"api_version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shopify/refs/heads/main/json-ld/shopify-context.jsonld
tags:
- Commerce
- Ecommerce
- Payments
- Retail
- Shopping Cart
- T1
- JSON-LD
- Linked Data
- Semantic Web
---
