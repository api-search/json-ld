---
class_count: 1
classes:
- MerchantRiskIndicator
context_file: json-ld/adyen-checkout-merchant-risk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-merchant-risk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Merchant Risk from Adyen.
layout: jsonld
name: Adyen Checkout Merchant Risk Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: addressMatch
  type: boolean
- container: ''
  name: deliveryAddressIndicator
  type: string
- container: ''
  name: deliveryEmail
  type: string
- container: ''
  name: deliveryEmailAddress
  type: string
- container: ''
  name: deliveryTimeframe
  type: string
- container: ''
  name: giftCardAmount
  type: string
- container: ''
  name: giftCardCount
  type: integer
- container: ''
  name: giftCardCurr
  type: string
- container: ''
  name: preOrderDate
  type: dateTime
- container: ''
  name: preOrderPurchase
  type: boolean
- container: ''
  name: preOrderPurchaseInd
  type: string
- container: ''
  name: reorderItems
  type: boolean
- container: ''
  name: reorderItemsInd
  type: string
- container: ''
  name: shipIndicator
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-merchant-risk-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MerchantRiskIndicator\": \"adyen:MerchantRiskIndicator\",\n    \"addressMatch\": {\n      \"@id\": \"adyen:addressMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deliveryAddressIndicator\": {\n      \"@id\": \"adyen:deliveryAddressIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryEmail\": {\n      \"@id\": \"adyen:deliveryEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryEmailAddress\": {\n      \"@id\": \"adyen:deliveryEmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryTimeframe\": {\n      \"@id\": \"adyen:deliveryTimeframe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"giftCardAmount\": {\n      \"@id\": \"adyen:giftCardAmount\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"giftCardCount\": {\n      \"@id\": \"adyen:giftCardCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"giftCardCurr\": {\n      \"@id\": \"adyen:giftCardCurr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preOrderDate\": {\n      \"@id\": \"adyen:preOrderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"preOrderPurchase\": {\n      \"@id\": \"adyen:preOrderPurchase\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"preOrderPurchaseInd\": {\n      \"@id\": \"adyen:preOrderPurchaseInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reorderItems\": {\n      \"@id\": \"adyen:reorderItems\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reorderItemsInd\": {\n      \"@id\": \"adyen:reorderItemsInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipIndicator\": {\n      \"@id\": \"adyen:shipIndicator\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-merchant-risk-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
