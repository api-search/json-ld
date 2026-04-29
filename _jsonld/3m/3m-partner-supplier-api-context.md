---
api_specs:
- filename: 3m-partner-supplier-api-openapi.yml
  format: yaml
  label: 3M Partner and Supplier API
  slug: partner-supplier-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/3m/refs/heads/main/openapi/3m-partner-supplier-api-openapi.yml
class_count: 14
classes:
- Delivery
- Order
- Invoice
- InvoiceList
- OrderItem
- Product
- OrderList
- CreateOrderRequest
- ProductPrice
- DeliveryList
- ProductList
- ShippingAddress
- description
- name
context_file: json-ld/3m-partner-supplier-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/3m/refs/heads/main/json-ld/3m-partner-supplier-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 3M Partner Supplier Api from 3M.
layout: jsonld
name: 3M Partner Supplier Api Context
namespaces:
- prefix: threeem
  uri: https://api.3m.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: availability
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: currency
  type: string
- container: set
  name: deliveries
  type: ''
- container: ''
  name: deliveryId
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: estimatedDelivery
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: invoiceId
  type: string
- container: set
  name: invoices
  type: ''
- container: set
  name: items
  type: ''
- container: ''
  name: orderId
  type: string
- container: set
  name: orders
  type: ''
- container: ''
  name: pricingTier
  type: string
- container: ''
  name: productId
  type: string
- container: set
  name: products
  type: ''
- container: ''
  name: quantity
  type: integer
- container: ''
  name: shippedAt
  type: dateTime
- container: ''
  name: sku
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: zip
  type: string
property_count: 32
provider_name: 3M
provider_slug: 3m
slug: 3m-partner-supplier-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"threeem\": \"https://api.3m.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Delivery\": \"threeem:Delivery\",\n    \"Order\": \"threeem:Order\",\n    \"Invoice\": \"threeem:Invoice\",\n    \"InvoiceList\": \"threeem:InvoiceList\",\n    \"OrderItem\": \"threeem:OrderItem\",\n    \"Product\": \"threeem:Product\",\n    \"OrderList\": \"threeem:OrderList\",\n    \"CreateOrderRequest\": \"threeem:CreateOrderRequest\",\n    \"ProductPrice\": \"threeem:ProductPrice\",\n    \"DeliveryList\": \"threeem:DeliveryList\",\n    \"ProductList\": \"threeem:ProductList\",\n    \"ShippingAddress\": \"threeem:ShippingAddress\",\n    \"availability\": {\n      \"@id\": \"threeem:availability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"threeem:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"threeem:category\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"threeem:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"threeem:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"threeem:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"threeem:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveries\": {\n      \"@id\": \"threeem:deliveries\",\n      \"@container\": \"@set\"\n    },\n    \"deliveryId\": {\n      \"@id\": \"threeem:deliveryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"dueDate\": {\n      \"@id\": \"threeem:dueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"threeem:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"estimatedDelivery\": {\n      \"@id\": \"threeem:estimatedDelivery\",\n      \"@type\": \"xsd:date\"\
  \n    },\n    \"expirationDate\": {\n      \"@id\": \"threeem:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"threeem:invoiceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"invoiceId\": {\n      \"@id\": \"threeem:invoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoices\": {\n      \"@id\": \"threeem:invoices\",\n      \"@container\": \"@set\"\n    },\n    \"items\": {\n      \"@id\": \"threeem:items\",\n      \"@container\": \"@set\"\n    },\n    \"name\": \"schema:name\",\n    \"orderId\": {\n      \"@id\": \"threeem:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orders\": {\n      \"@id\": \"threeem:orders\",\n      \"@container\": \"@set\"\n    },\n    \"pricingTier\": {\n      \"@id\": \"threeem:pricingTier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"threeem:productId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"products\": {\n      \"@id\": \"threeem:products\"\
  ,\n      \"@container\": \"@set\"\n    },\n    \"quantity\": {\n      \"@id\": \"threeem:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shippedAt\": {\n      \"@id\": \"threeem:shippedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sku\": {\n      \"@id\": \"threeem:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"threeem:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"threeem:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"threeem:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"threeem:totalAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"threeem:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"threeem:unitPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"zip\": {\n      \"@id\": \"threeem:zip\",\n    \
  \  \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/3m/refs/heads/main/json-ld/3m-partner-supplier-api-context.jsonld
tags:
- Industrial
- Manufacturing
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
