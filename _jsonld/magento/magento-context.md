---
api_specs:
- filename: magento-rest-api-openapi.yml
  format: yaml
  label: Magento REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/openapi/magento-rest-api-openapi.yml
- filename: magento-webhooks-asyncapi.yml
  format: yaml
  label: Adobe Commerce Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/asyncapi/magento-webhooks-asyncapi.yml
- filename: magento-events-asyncapi.yml
  format: yaml
  label: Adobe Commerce Eventing
  slug: events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/asyncapi/magento-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/magento-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/json-ld/magento-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Magento from magento.
layout: jsonld
name: Magento Context
namespaces:
- prefix: magento
  uri: https://developer.adobe.com/commerce/webapi/rest/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: s
  uri: https://schema.org/
properties:
- container: ''
  name: Order
  type: ''
- container: ''
  name: OrderItem
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: InventorySource
  type: ''
- container: ''
  name: StoreConfig
  type: ''
property_count: 8
provider_name: magento
provider_slug: magento
slug: magento-context
source_filename: magento-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"magento\": \"https://developer.adobe.com/commerce/webapi/rest/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"s\": \"https://schema.org/\",\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"entity_id\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"increment_id\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"magento:orderState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customer_id\": {\n          \"@id\": \"schema:customer\",\n     \
  \     \"@type\": \"xsd:integer\"\n        },\n        \"customer_email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customer_firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customer_lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customer_is_guest\": {\n          \"@id\": \"magento:isGuestOrder\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"grand_total\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"subtotal\": {\n          \"@id\": \"magento:subtotal\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"tax_amount\": {\n          \"@id\": \"magento:taxAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"shipping_amount\": {\n          \"@id\": \"magento:shippingAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"discount_amount\": {\n          \"@id\": \"magento:discountAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"base_currency_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"order_currency_code\": {\n          \"@id\": \"magento:orderCurrencyCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"coupon_code\": {\n          \"@id\": \"schema:discount\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shipping_method\": {\n          \"@id\": \"schema:deliveryMethod\",\n          \"@type\": \"xsd:string\"\n        },\n        \"billing_address\": {\n          \"@id\": \"schema:billingAddress\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"payment\": {\n          \"@id\": \"schema:paymentMethod\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"OrderItem\": {\n      \"@id\": \"schema:OrderItem\",\n      \"@context\": {\n        \"item_id\": {\n          \"@id\": \"magento:orderItemId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sku\": {\n          \"@id\": \"gr:hasStockKeepingUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"product_id\": {\n          \"@id\": \"schema:product\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"product_type\": {\n          \"@id\": \"magento:productType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"qty_ordered\": {\n          \"@id\": \"schema:orderQuantity\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"qty_shipped\": {\n          \"@id\": \"magento:qtyShipped\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"qty_invoiced\": {\n          \"@id\": \"magento:qtyInvoiced\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"row_total\": {\n          \"@id\": \"magento:rowTotal\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"tax_amount\": {\n          \"@id\": \"magento:taxAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"tax_percent\": {\n          \"@id\": \"magento:taxPercent\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"discount_amount\": {\n          \"@id\": \"magento:discountAmount\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n   \
  \     \"id\": {\n          \"@id\": \"magento:productEntityId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sku\": {\n          \"@id\": \"gr:hasStockKeepingUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": {\n          \"@id\": \"magento:productStatus\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"visibility\": {\n          \"@id\": \"magento:productVisibility\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"type_id\": {\n          \"@id\": \"magento:productType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attribute_set_id\": {\n          \"@id\": \"magento:attributeSetId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"weight\": {\n          \"@id\": \"schema:weight\"\
  ,\n          \"@type\": \"xsd:decimal\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"product_links\": {\n          \"@id\": \"schema:isRelatedTo\",\n          \"@container\": \"@set\"\n        },\n        \"media_gallery_entries\": {\n          \"@id\": \"schema:image\",\n          \"@container\": \"@set\"\n        },\n        \"tier_prices\": {\n          \"@id\": \"gr:hasPriceSpecification\",\n          \"@container\": \"@set\"\n        },\n        \"custom_attributes\": {\n          \"@id\": \"magento:customAttributes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Category\": {\n      \"@id\": \"schema:CategoryCode\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"magento:categoryEntityId\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"parent_id\": {\n          \"@id\": \"schema:broader\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"is_active\": {\n          \"@id\": \"magento:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"position\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"level\": {\n          \"@id\": \"magento:treeLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"path\": {\n          \"@id\": \"magento:categoryPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"include_in_menu\": {\n          \"@id\": \"magento:includeInMenu\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"children_data\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"magento:customerEntityId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"group_id\": {\n          \"@id\": \"magento:customerGroupId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"store_id\": {\n          \"@id\": \"magento:storeId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"website_id\": {\n  \
  \        \"@id\": \"magento:websiteId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"company\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"street\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@container\": \"@set\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region_code\": {\n          \"@id\": \"magento:regionCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country_id\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"telephone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"InventorySource\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"source_code\": {\n          \"@id\": \"magento:sourceCode\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"schema:isAccessibleForFree\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"country_id\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"street\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postcode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"StoreConfig\": {\n      \"@id\": \"schema:WebSite\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"magento:storeId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"code\": {\n          \"@id\": \"magento:storeCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"website_id\": {\n          \"@id\": \"magento:websiteId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"locale\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"base_currency_code\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timezone\": {\n          \"@id\": \"magento:timezone\",\n       \
  \   \"@type\": \"xsd:string\"\n        },\n        \"base_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"secure_base_url\": {\n          \"@id\": \"magento:secureBaseUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/json-ld/magento-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
