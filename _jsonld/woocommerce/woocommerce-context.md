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
class_count: 0
classes: []
context_file: json-ld/woocommerce-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce from WooCommerce.
layout: jsonld
name: Woocommerce Context
namespaces:
- prefix: wc
  uri: https://developer.woocommerce.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Product
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Coupon
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: PostalAddress
  type: ''
- container: ''
  name: ProductCategory
  type: ''
- container: ''
  name: LineItem
  type: ''
property_count: 8
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-context
source_filename: woocommerce-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wc\": \"https://developer.woocommerce.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"slug\": \"wc:slug\",\n        \"permalink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": \"schema:description\",\n        \"short_description\": \"schema:disambiguatingDescription\",\n        \"sku\": \"schema:sku\",\n        \"price\": {\n          \"@id\": \"gr:hasCurrencyValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"regular_price\": {\n          \"@id\": \"gr:hasCurrencyValue\",\n          \"@type\": \"xsd:decimal\"\n       \
  \ },\n        \"sale_price\": {\n          \"@id\": \"wc:salePrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"on_sale\": {\n          \"@id\": \"wc:onSale\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"type\": \"wc:productType\",\n        \"status\": \"schema:creativeWorkStatus\",\n        \"featured\": {\n          \"@id\": \"wc:featured\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"virtual\": {\n          \"@id\": \"wc:virtual\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"downloadable\": {\n          \"@id\": \"wc:downloadable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"manage_stock\": {\n          \"@id\": \"wc:manageStock\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"stock_quantity\": {\n          \"@id\": \"gr:quantityProductOrService\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"stock_status\": \"wc:stockStatus\",\n        \"weight\": {\n          \"@id\"\
  : \"schema:weight\",\n          \"@type\": \"xsd:string\"\n        },\n        \"average_rating\": {\n          \"@id\": \"schema:ratingValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"rating_count\": {\n          \"@id\": \"schema:reviewCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_sales\": {\n          \"@id\": \"wc:totalSales\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"categories\": {\n          \"@id\": \"schema:category\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"images\": {\n          \"@id\": \"schema:image\",\n          \"@container\": \"@set\"\
  \n        },\n        \"attributes\": {\n          \"@id\": \"wc:attribute\",\n          \"@container\": \"@set\"\n        },\n        \"variations\": {\n          \"@id\": \"schema:hasVariant\",\n          \"@container\": \"@set\"\n        },\n        \"meta_data\": {\n          \"@id\": \"wc:metaData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"number\": \"schema:orderNumber\",\n        \"order_key\": \"wc:orderKey\",\n        \"status\": \"schema:orderStatus\",\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"total\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"discount_total\": {\n          \"@id\": \"wc:discountTotal\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"shipping_total\": {\n          \"@id\": \"wc:shippingTotal\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"total_tax\": {\n          \"@id\": \"wc:totalTax\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"customer_id\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"@id\"\n        },\n        \"customer_note\": \"schema:description\",\n        \"payment_method\": {\n          \"@id\": \"schema:paymentMethod\"\n        },\n        \"payment_method_title\": {\n          \"@id\": \"schema:paymentMethodId\"\n        },\n        \"transaction_id\": \"wc:transactionId\",\n        \"billing\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"shipping\": {\n          \"@id\": \"schema:deliveryAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"line_items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"coupon_lines\": {\n          \"@id\": \"schema:discount\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"date_created\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_completed\": {\n          \"@id\": \"wc:dateCompleted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_paid\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"meta_data\": {\n          \"@id\": \"wc:metaData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"username\": \"schema:alternateName\",\n        \"role\": \"wc:userRole\"\
  ,\n        \"billing\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"shipping\": {\n          \"@id\": \"wc:shippingAddress\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"is_paying_customer\": {\n          \"@id\": \"wc:isPayingCustomer\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"orders_count\": {\n          \"@id\": \"wc:ordersCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_spent\": {\n          \"@id\": \"wc:totalSpent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"avatar_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"date_created\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"meta_data\": {\n\
  \          \"@id\": \"wc:metaData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Coupon\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"code\": \"schema:serialNumber\",\n        \"amount\": {\n          \"@id\": \"wc:discountAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"discount_type\": \"wc:discountType\",\n        \"description\": \"schema:description\",\n        \"date_expires\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"usage_count\": {\n          \"@id\": \"wc:usageCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"usage_limit\": {\n          \"@id\": \"wc:usageLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"usage_limit_per_user\": {\n          \"@id\": \"wc:usageLimitPerUser\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"individual_use\": {\n\
  \          \"@id\": \"wc:individualUse\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"product_ids\": {\n          \"@id\": \"schema:itemOffered\",\n          \"@container\": \"@set\"\n        },\n        \"minimum_amount\": {\n          \"@id\": \"schema:minPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"maximum_amount\": {\n          \"@id\": \"schema:maxPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"meta_data\": {\n          \"@id\": \"wc:metaData\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"wc:Webhook\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"status\"\
  : \"schema:status\",\n        \"topic\": \"wc:webhookTopic\",\n        \"resource\": \"wc:webhookResource\",\n        \"event\": \"wc:webhookEvent\",\n        \"delivery_url\": {\n          \"@id\": \"wc:deliveryUrl\",\n          \"@type\": \"@id\"\n        },\n        \"date_created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"date_modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PostalAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"company\": \"schema:legalName\",\n        \"address_1\": \"schema:streetAddress\",\n        \"address_2\": \"wc:streetAddress2\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postcode\": \"schema:postalCode\",\n        \"\
  country\": \"schema:addressCountry\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\"\n      }\n    },\n\n    \"ProductCategory\": {\n      \"@id\": \"schema:Thing\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"slug\": \"wc:slug\",\n        \"description\": \"schema:description\",\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"count\": {\n          \"@id\": \"wc:productCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"LineItem\": {\n      \"@id\": \"schema:OrderItem\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"product_id\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@type\": \"@id\"\n        },\n        \"\
  variation_id\": {\n          \"@id\": \"wc:variationId\",\n          \"@type\": \"@id\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:orderQuantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"subtotal\": {\n          \"@id\": \"wc:subtotal\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"total\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sku\": \"schema:sku\",\n        \"price\": {\n          \"@id\": \"gr:hasCurrencyValue\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-context.jsonld
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
