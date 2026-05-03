---
api_specs:
- filename: squarespace-commerce-api-openapi.yml
  format: yaml
  label: Squarespace Commerce API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-commerce-api-openapi.yml
- filename: squarespace-orders-api-openapi.yml
  format: yaml
  label: Squarespace Orders API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-orders-api-openapi.yml
- filename: squarespace-products-api-openapi.yml
  format: yaml
  label: Squarespace Products API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-products-api-openapi.yml
- filename: squarespace-inventory-api-openapi.yml
  format: yaml
  label: Squarespace Inventory API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-inventory-api-openapi.yml
- filename: squarespace-profiles-api-openapi.yml
  format: yaml
  label: Squarespace Profiles API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-profiles-api-openapi.yml
- filename: squarespace-transactions-api-openapi.yml
  format: yaml
  label: Squarespace Transactions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-transactions-api-openapi.yml
- filename: squarespace-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Squarespace Webhook Subscriptions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/openapi/squarespace-webhook-subscriptions-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/squarespace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/json-ld/squarespace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Squarespace from Squarespace.
layout: jsonld
name: Squarespace Context
namespaces:
- prefix: sqsp
  uri: https://developers.squarespace.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Order
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: ProductVariant
  type: ''
- container: ''
  name: ProductImage
  type: ''
- container: ''
  name: LineItem
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: Profile
  type: ''
- container: ''
  name: TransactionDocument
  type: ''
- container: ''
  name: Payment
  type: ''
- container: ''
  name: WebhookSubscription
  type: ''
- container: ''
  name: Money
  type: ''
- container: ''
  name: InventoryItem
  type: ''
property_count: 12
provider_name: Squarespace
provider_slug: squarespace
slug: squarespace-context
source_filename: squarespace-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sqsp\": \"https://developers.squarespace.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Order\": {\n      \"@id\": \"sqsp:Order\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"orderNumber\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"channel\": \"sqsp:channel\",\n        \"testmode\": {\n          \"@id\": \"sqsp:testmode\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"customerEmail\": {\n          \"@id\": \"schema:email\"\n        },\n        \"billingAddress\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\": \"@id\"\n        },\n        \"shippingAddress\": {\n          \"@id\": \"schema:shippingAddress\",\n          \"@type\": \"@id\"\n        },\n        \"fulfillmentStatus\": \"sqsp:fulfillmentStatus\"\
  ,\n        \"lineItems\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"fulfillments\": {\n          \"@id\": \"sqsp:fulfillments\",\n          \"@container\": \"@set\"\n        },\n        \"totals\": \"sqsp:totals\",\n        \"refundedTotal\": \"sqsp:refundedTotal\",\n        \"priceTaxInterpretation\": \"sqsp:priceTaxInterpretation\",\n        \"externalOrderReference\": \"sqsp:externalOrderReference\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"schema:additionalType\",\n        \"storePageId\": \"sqsp:storePageId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\
  ,\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"urlSlug\": \"sqsp:urlSlug\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"isVisible\": {\n          \"@id\": \"sqsp:isVisible\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"variants\": {\n          \"@id\": \"schema:hasVariant\",\n          \"@container\": \"@set\"\n        },\n        \"images\": {\n          \"@id\": \"schema:image\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ProductVariant\": {\n      \"@id\": \"schema:ProductModel\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"sku\": \"schema:sku\",\n\
  \        \"pricing\": \"sqsp:pricing\",\n        \"stock\": \"sqsp:stock\",\n        \"attributes\": \"sqsp:attributes\"\n      }\n    },\n\n    \"ProductImage\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"altText\": \"schema:alternateName\",\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"LineItem\": {\n      \"@id\": \"schema:OrderItem\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"variantId\": \"sqsp:variantId\",\n        \"sku\": \"schema:sku\",\n        \"productId\": \"sqsp:productId\",\n        \"productName\": \"schema:name\",\n        \"quantity\": {\n          \"@id\": \"schema:orderQuantity\",\n       \
  \   \"@type\": \"xsd:integer\"\n        },\n        \"unitPricePaid\": \"schema:price\",\n        \"lineItemType\": \"sqsp:lineItemType\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"address1\": \"schema:streetAddress\",\n        \"address2\": \"sqsp:address2\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"countryCode\": \"schema:addressCountry\",\n        \"postalCode\": \"schema:postalCode\",\n        \"phone\": \"schema:telephone\"\n      }\n    },\n\n    \"Profile\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\":\
  \ \"schema:email\",\n        \"hasAccount\": {\n          \"@id\": \"sqsp:hasAccount\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isCustomer\": {\n          \"@id\": \"sqsp:isCustomer\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"address\": \"schema:address\",\n        \"commerceStats\": \"sqsp:commerceStats\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TransactionDocument\": {\n      \"@id\": \"schema:Invoice\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"totalSales\": \"sqsp:totalSales\",\n        \"totalNetPayment\": \"sqsp:totalNetPayment\",\n        \"payments\": {\n          \"@id\": \"sqsp:payments\",\n          \"@container\": \"@set\"\n        },\n        \"lineItems\": {\n          \"@id\": \"sqsp:transactionLineItems\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"orderDocumentType\": \"sqsp:orderDocumentType\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"schema:PaymentMethod\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"paymentGateway\": \"sqsp:paymentGateway\",\n        \"creditCardType\": \"sqsp:creditCardType\",\n        \"amount\": \"schema:price\",\n        \"refundedAmount\": \"sqsp:refundedAmount\",\n        \"externalTransactionId\": \"sqsp:externalTransactionId\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookSubscription\": {\n      \"@id\": \"sqsp:WebhookSubscription\",\n      \"@context\": {\n        \"id\":\
  \ \"@id\",\n        \"endpointUrl\": {\n          \"@id\": \"sqsp:endpointUrl\",\n          \"@type\": \"@id\"\n        },\n        \"topics\": {\n          \"@id\": \"sqsp:topics\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Money\": {\n      \"@id\": \"schema:MonetaryAmount\",\n      \"@context\": {\n        \"value\": \"schema:value\",\n        \"currency\": \"schema:currency\"\n      }\n    },\n\n    \"InventoryItem\": {\n      \"@id\": \"sqsp:InventoryItem\",\n      \"@context\": {\n        \"variantId\": \"sqsp:variantId\",\n        \"sku\": \"schema:sku\",\n        \"descriptor\": \"schema:description\",\n        \"isUnlimited\": {\n          \"@id\": \"sqsp:isUnlimited\",\n          \"@type\": \"xsd:boolean\"\n    \
  \    },\n        \"isTracked\": {\n          \"@id\": \"sqsp:isTracked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:inventoryLevel\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/squarespace/refs/heads/main/json-ld/squarespace-context.jsonld
tags:
- Commerce
- E-Commerce
- Marketing
- Payments
- Retail
- Website Builder
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
