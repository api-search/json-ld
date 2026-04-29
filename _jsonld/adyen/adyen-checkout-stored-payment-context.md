---
class_count: 4
classes:
- StoredPaymentMethodDetails
- StoredPaymentMethodResource
- StoredPaymentMethod
- name
context_file: json-ld/adyen-checkout-stored-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-stored-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Stored Payment from Adyen.
layout: jsonld
name: Adyen Checkout Stored Payment Context
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
  name: checkoutAttemptId
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: expiryMonth
  type: string
- container: ''
  name: expiryYear
  type: string
- container: ''
  name: externalResponseCode
  type: string
- container: ''
  name: externalTokenReference
  type: string
- container: ''
  name: holderName
  type: string
- container: ''
  name: iban
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: issuerName
  type: string
- container: ''
  name: lastFour
  type: string
- container: ''
  name: networkTxReference
  type: string
- container: ''
  name: ownerName
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperReference
  type: string
- container: set
  name: supportedRecurringProcessingModels
  type: string
- container: ''
  name: bankAccountNumber
  type: string
- container: ''
  name: bankLocationId
  type: string
- container: ''
  name: label
  type: string
- container: set
  name: supportedShopperInteractions
  type: string
property_count: 23
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-stored-payment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoredPaymentMethodDetails\": \"adyen:StoredPaymentMethodDetails\",\n    \"StoredPaymentMethodResource\": \"adyen:StoredPaymentMethodResource\",\n    \"StoredPaymentMethod\": \"adyen:StoredPaymentMethod\",\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"expiryMonth\": {\n      \"@id\": \"adyen:expiryMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryYear\": {\n      \"@id\": \"adyen:expiryYear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalResponseCode\": {\n      \"@id\": \"adyen:externalResponseCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalTokenReference\": {\n      \"@id\": \"adyen:externalTokenReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holderName\": {\n      \"@id\": \"adyen:holderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iban\": {\n      \"@id\": \"adyen:iban\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerName\": {\n      \"@id\": \"adyen:issuerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastFour\": {\n      \"@id\": \"adyen:lastFour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"networkTxReference\"\
  : {\n      \"@id\": \"adyen:networkTxReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerName\": {\n      \"@id\": \"adyen:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedRecurringProcessingModels\": {\n      \"@id\": \"adyen:supportedRecurringProcessingModels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountNumber\": {\n      \"@id\": \"adyen:bankAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankLocationId\": {\n      \"@id\": \"adyen:bankLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"adyen:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedShopperInteractions\": {\n      \"@id\": \"adyen:supportedShopperInteractions\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-stored-payment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
