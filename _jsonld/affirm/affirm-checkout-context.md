---
api_specs:
- filename: affirm-direct-api-openapi.yml
  format: yaml
  label: Affirm Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-direct-api-openapi.yml
- filename: affirm-checkout-openapi.yml
  format: yaml
  label: Affirm Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-checkout-openapi.yml
- filename: affirm-transactions-openapi.yml
  format: yaml
  label: Affirm Transactions API
  slug: transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-transactions-openapi.yml
- filename: affirm-promos-openapi.yml
  format: yaml
  label: Affirm Promos API
  slug: promos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-promos-openapi.yml
- filename: affirm-disputes-openapi.yml
  format: yaml
  label: Affirm Disputes API
  slug: disputes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-disputes-openapi.yml
class_count: 11
classes:
- DiscountObject
- ItemObject
- MerchantObject
- name
- ContactObject
- email
- CheckoutRequest
- StoreObject
- NameObject
- AddressObject
- Checkout
context_file: json-ld/affirm-checkout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-checkout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm Checkout from affirm.
layout: jsonld
name: Affirm Checkout Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: discountAmount
  type: integer
- container: ''
  name: discountDisplayName
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: unitPrice
  type: integer
- container: ''
  name: qty
  type: integer
- container: ''
  name: itemImageUrl
  type: reference
- container: ''
  name: itemUrl
  type: reference
- container: set
  name: categories
  type: ''
- container: ''
  name: publicApiKey
  type: string
- container: ''
  name: userConfirmationUrl
  type: reference
- container: ''
  name: userCancelUrl
  type: reference
- container: ''
  name: userConfirmationUrlAction
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: merchant
  type: string
- container: ''
  name: shipping
  type: string
- container: ''
  name: billing
  type: string
- container: ''
  name: store
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: discounts
  type: reference
- container: ''
  name: metadata
  type: reference
- container: ''
  name: orderId
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: financingProgram
  type: string
- container: ''
  name: shippingAmount
  type: integer
- container: ''
  name: taxAmount
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: checkoutExpiration
  type: dateTime
- container: ''
  name: expirationTime
  type: dateTime
- container: ''
  name: first
  type: string
- container: ''
  name: last
  type: string
- container: ''
  name: full
  type: string
- container: ''
  name: line1
  type: string
- container: ''
  name: line2
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zipcode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: checkoutId
  type: string
- container: ''
  name: checkoutStatus
  type: string
- container: ''
  name: checkoutFlowType
  type: string
- container: ''
  name: financialProgramName
  type: string
- container: ''
  name: financialProgramExternalName
  type: string
- container: ''
  name: billingFrequency
  type: string
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: productType
  type: string
- container: ''
  name: meta
  type: reference
- container: ''
  name: userTimezone
  type: string
- container: ''
  name: trackingUuid
  type: string
property_count: 50
provider_name: affirm
provider_slug: affirm
slug: affirm-checkout-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DiscountObject\": \"affirm:DiscountObject\",\n    \"discountAmount\": {\n      \"@id\": \"affirm:discount_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"discountDisplayName\": {\n      \"@id\": \"affirm:discount_display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemObject\": \"affirm:ItemObject\",\n    \"displayName\": {\n      \"@id\": \"affirm:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"affirm:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"affirm:unit_price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"qty\": {\n      \"@id\": \"affirm:qty\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"itemImageUrl\": {\n   \
  \   \"@id\": \"affirm:item_image_url\",\n      \"@type\": \"@id\"\n    },\n    \"itemUrl\": {\n      \"@id\": \"affirm:item_url\",\n      \"@type\": \"@id\"\n    },\n    \"categories\": {\n      \"@id\": \"affirm:categories\",\n      \"@container\": \"@set\"\n    },\n    \"MerchantObject\": \"affirm:MerchantObject\",\n    \"publicApiKey\": {\n      \"@id\": \"affirm:public_api_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userConfirmationUrl\": {\n      \"@id\": \"affirm:user_confirmation_url\",\n      \"@type\": \"@id\"\n    },\n    \"userCancelUrl\": {\n      \"@id\": \"affirm:user_cancel_url\",\n      \"@type\": \"@id\"\n    },\n    \"userConfirmationUrlAction\": {\n      \"@id\": \"affirm:user_confirmation_url_action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"ContactObject\": \"affirm:ContactObject\",\n    \"address\": {\n      \"@id\": \"affirm:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n \
  \   \"phoneNumber\": {\n      \"@id\": \"affirm:phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckoutRequest\": \"affirm:CheckoutRequest\",\n    \"merchant\": {\n      \"@id\": \"affirm:merchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipping\": {\n      \"@id\": \"affirm:shipping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billing\": {\n      \"@id\": \"affirm:billing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"affirm:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"affirm:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discounts\": {\n      \"@id\": \"affirm:discounts\",\n      \"@type\": \"@id\"\n    },\n    \"metadata\": {\n      \"@id\": \"affirm:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"orderId\": {\n      \"@id\": \"affirm:order_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"affirm:currency\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"financingProgram\": {\n      \"@id\": \"affirm:financing_program\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingAmount\": {\n      \"@id\": \"affirm:shipping_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taxAmount\": {\n      \"@id\": \"affirm:tax_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"affirm:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"checkoutExpiration\": {\n      \"@id\": \"affirm:checkout_expiration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expirationTime\": {\n      \"@id\": \"affirm:expiration_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"StoreObject\": \"affirm:StoreObject\",\n    \"NameObject\": \"affirm:NameObject\",\n    \"first\": {\n      \"@id\": \"affirm:first\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last\": {\n      \"@id\": \"affirm:last\",\n      \"@type\": \"xsd:string\"\n    },\n    \"full\": {\n  \
  \    \"@id\": \"affirm:full\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressObject\": \"affirm:AddressObject\",\n    \"line1\": {\n      \"@id\": \"affirm:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line2\": {\n      \"@id\": \"affirm:line2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"affirm:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"affirm:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zipcode\": {\n      \"@id\": \"affirm:zipcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"affirm:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Checkout\": \"affirm:Checkout\",\n    \"checkoutId\": {\n      \"@id\": \"affirm:checkout_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutStatus\": {\n      \"@id\": \"affirm:checkout_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutFlowType\": {\n      \"@id\": \"affirm:checkout_flow_type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"financialProgramName\": {\n      \"@id\": \"affirm:financial_program_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"financialProgramExternalName\": {\n      \"@id\": \"affirm:financial_program_external_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingFrequency\": {\n      \"@id\": \"affirm:billing_frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"affirm:api_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productType\": {\n      \"@id\": \"affirm:product_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"affirm:meta\",\n      \"@type\": \"@id\"\n    },\n    \"userTimezone\": {\n      \"@id\": \"affirm:user_timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingUuid\": {\n      \"@id\": \"affirm:tracking_uuid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-checkout-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
