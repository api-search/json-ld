---
api_specs:
- filename: streamone-ion-openapi.yml
  format: yaml
  label: TD SYNNEX StreamOne Ion API
  slug: streamone-ion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tech-data/refs/heads/main/openapi/streamone-ion-openapi.yml
class_count: 55
classes:
- Customer
- customerId
- customerName
- customerEmail
- customerPhone
- customerStatus
- customerAddress
- Order
- orderId
- orderStatus
- orderDate
- orderTotal
- orderCurrency
- orderItems
- OrderItem
- orderItemId
- productId
- productName
- quantity
- unitPrice
- totalPrice
- Subscription
- subscriptionId
- subscriptionStatus
- subscriptionStartDate
- subscriptionEndDate
- billingPeriod
- renewalDate
- Product
- vendorId
- vendorName
- productCategory
- productVertical
- productPrice
- productCurrency
- Cart
- cartId
- cartStatus
- cartTotal
- cartItems
- Report
- reportId
- reportName
- reportCategory
- Address
- street
- city
- state
- postalCode
- country
- Pagination
- page
- pageSize
- totalRecords
- totalPages
context_file: json-ld/tech-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tech-data/refs/heads/main/json-ld/tech-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tech Data from Tech Data.
layout: jsonld
name: Tech Data Context
namespaces:
- prefix: td
  uri: https://raw.githubusercontent.com/api-evangelist/tech-data/main/json-ld/tech-data-context.jsonld#
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Tech Data
provider_slug: tech-data
slug: tech-data-context
source_filename: tech-data-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"td\": \"https://raw.githubusercontent.com/api-evangelist/tech-data/main/json-ld/tech-data-context.jsonld#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Customer\": \"schema:Organization\",\n    \"customerId\": \"schema:identifier\",\n    \"customerName\": \"schema:name\",\n    \"customerEmail\": \"schema:email\",\n    \"customerPhone\": \"schema:telephone\",\n    \"customerStatus\": \"td:customerStatus\",\n    \"customerAddress\": \"schema:address\",\n\n    \"Order\": \"schema:Order\",\n    \"orderId\": \"schema:orderNumber\",\n    \"orderStatus\": \"schema:orderStatus\",\n    \"orderDate\": \"schema:orderDate\",\n    \"orderTotal\": \"schema:price\",\n    \"orderCurrency\": \"schema:priceCurrency\",\n    \"orderItems\": \"schema:orderedItem\",\n\n    \"OrderItem\": \"schema:OrderItem\",\n    \"orderItemId\": \"schema:identifier\",\n    \"productId\": \"schema:identifier\",\n    \"productName\": \"\
  schema:name\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"unitPrice\": \"schema:price\",\n    \"totalPrice\": \"schema:totalPrice\",\n\n    \"Subscription\": \"schema:Subscription\",\n    \"subscriptionId\": \"schema:identifier\",\n    \"subscriptionStatus\": \"td:subscriptionStatus\",\n    \"subscriptionStartDate\": \"schema:validFrom\",\n    \"subscriptionEndDate\": \"schema:validThrough\",\n    \"billingPeriod\": \"td:billingPeriod\",\n    \"renewalDate\": \"td:renewalDate\",\n\n    \"Product\": \"schema:Product\",\n    \"vendorId\": \"schema:identifier\",\n    \"vendorName\": \"schema:name\",\n    \"productCategory\": \"schema:category\",\n    \"productVertical\": \"td:vertical\",\n    \"productPrice\": \"schema:price\",\n    \"productCurrency\": \"schema:priceCurrency\",\n\n    \"Cart\": \"schema:ShoppingCart\",\n    \"cartId\": \"schema:identifier\",\n    \"cartStatus\": \"td:cartStatus\",\n    \"cartTotal\": \"schema:price\",\n    \"cartItems\": \"schema:containsProduct\"\
  ,\n\n    \"Report\": \"schema:Report\",\n    \"reportId\": \"schema:identifier\",\n    \"reportName\": \"schema:name\",\n    \"reportCategory\": \"schema:about\",\n\n    \"Address\": \"schema:PostalAddress\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"Pagination\": \"td:Pagination\",\n    \"page\": \"td:page\",\n    \"pageSize\": \"td:pageSize\",\n    \"totalRecords\": \"td:totalRecords\",\n    \"totalPages\": \"td:totalPages\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tech-data/refs/heads/main/json-ld/tech-data-context.jsonld
tags:
- Cloud
- Distribution
- Information Technology
- Partner
- JSON-LD
- Linked Data
- Semantic Web
---
