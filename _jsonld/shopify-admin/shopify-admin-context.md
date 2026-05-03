---
api_specs:
- filename: shopify-admin-rest-openapi.yml
  format: yaml
  label: Shopify Admin REST API
  slug: shopify-admin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/openapi/shopify-admin-rest-openapi.yml
class_count: 41
classes:
- Product
- title
- body_html
- vendor
- product_type
- status
- tags
- handle
- variants
- images
- price
- sku
- Order
- order_number
- financial_status
- fulfillment_status
- total_price
- currency
- line_items
- customer
- shipping_address
- billing_address
- Customer
- email
- first_name
- last_name
- phone
- addresses
- Location
- address1
- city
- province
- country
- zip
- Webhook
- address
- topic
- Shop
- name
- domain
- plan_name
context_file: json-ld/shopify-admin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/json-ld/shopify-admin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shopify Admin from Shopify Admin API.
layout: jsonld
name: Shopify Admin Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shopify
  uri: https://shopify.dev/docs/api/admin-rest/latest/resources/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: published_at
  type: dateTime
property_count: 3
provider_name: Shopify Admin API
provider_slug: shopify-admin
slug: shopify-admin-context
source_filename: shopify-admin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shopify\": \"https://shopify.dev/docs/api/admin-rest/latest/resources/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"title\": \"schema:name\",\n    \"body_html\": \"schema:description\",\n    \"vendor\": \"schema:brand\",\n    \"product_type\": \"schema:category\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"published_at\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:status\",\n    \"tags\": \"schema:keywords\",\n    \"handle\": \"schema:identifier\",\n    \"variants\": \"schema:hasVariant\",\n    \"images\": \"schema:image\",\n    \"price\": \"schema:price\",\n    \"sku\": \"schema:sku\"\
  ,\n\n    \"Order\": \"schema:Order\",\n    \"order_number\": \"schema:orderNumber\",\n    \"financial_status\": \"schema:paymentStatus\",\n    \"fulfillment_status\": \"schema:orderStatus\",\n    \"total_price\": \"schema:totalPrice\",\n    \"currency\": \"schema:priceCurrency\",\n    \"line_items\": \"schema:orderedItem\",\n    \"customer\": \"schema:customer\",\n    \"shipping_address\": \"schema:deliveryAddress\",\n    \"billing_address\": \"schema:billingAddress\",\n\n    \"Customer\": \"schema:Person\",\n    \"email\": \"schema:email\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"phone\": \"schema:telephone\",\n    \"addresses\": \"schema:address\",\n\n    \"Location\": \"schema:Place\",\n    \"address1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"province\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"zip\": \"schema:postalCode\",\n\n    \"Webhook\": \"schema:Action\"\
  ,\n    \"address\": \"schema:url\",\n    \"topic\": \"schema:name\",\n\n    \"Shop\": \"schema:Store\",\n    \"name\": \"schema:name\",\n    \"domain\": \"schema:url\",\n    \"plan_name\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shopify-admin/refs/heads/main/json-ld/shopify-admin-context.jsonld
tags:
- Commerce
- Ecommerce
- Admin
- Products
- Orders
- Customers
- JSON-LD
- Linked Data
- Semantic Web
---
