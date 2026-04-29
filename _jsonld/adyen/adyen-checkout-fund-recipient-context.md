---
class_count: 1
classes:
- FundRecipient
context_file: json-ld/adyen-checkout-fund-recipient-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-fund-recipient-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Fund Recipient from Adyen.
layout: jsonld
name: Adyen Checkout Fund Recipient Context
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
  name: billingAddress
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: storedPaymentMethodId
  type: string
- container: ''
  name: subMerchant
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: walletIdentifier
  type: string
- container: ''
  name: walletOwnerTaxId
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-fund-recipient-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FundRecipient\": \"adyen:FundRecipient\",\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subMerchant\": {\n      \"\
  @id\": \"adyen:subMerchant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"walletIdentifier\": {\n      \"@id\": \"adyen:walletIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"walletOwnerTaxId\": {\n      \"@id\": \"adyen:walletOwnerTaxId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-fund-recipient-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
