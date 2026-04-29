---
api_specs:
- filename: apple-pay-js-openapi.yml
  format: yaml
  label: Apple Pay JS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apple-pay/refs/heads/main/openapi/apple-pay-js-openapi.yml
- filename: apple-pay-payment-token-openapi.yml
  format: yaml
  label: Apple Pay Payment Token API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apple-pay/refs/heads/main/openapi/apple-pay-payment-token-openapi.yml
class_count: 0
classes: []
context_file: json-ld/apple-pay-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apple-pay/refs/heads/main/json-ld/apple-pay-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apple Pay from Apple Pay.
layout: jsonld
name: Apple Pay Context
namespaces:
- prefix: applepay
  uri: https://developer.apple.com/schemas/apple-pay/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: PaymentRequest
  type: ''
- container: ''
  name: LineItem
  type: ''
- container: ''
  name: PaymentToken
  type: ''
- container: ''
  name: PaymentData
  type: ''
- container: ''
  name: PaymentDataHeader
  type: ''
- container: ''
  name: PaymentMethod
  type: ''
- container: ''
  name: PaymentContact
  type: ''
- container: ''
  name: MerchantSession
  type: ''
- container: ''
  name: ShippingMethod
  type: ''
- container: ''
  name: DecryptedPaymentData
  type: ''
property_count: 10
provider_name: Apple Pay
provider_slug: apple-pay
slug: apple-pay-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"applepay\": \"https://developer.apple.com/schemas/apple-pay/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"PaymentRequest\": {\n      \"@id\": \"applepay:PaymentRequest\",\n      \"@context\": {\n        \"countryCode\": \"schema:addressCountry\",\n        \"currencyCode\": \"schema:priceCurrency\",\n        \"supportedNetworks\": \"applepay:supportedNetworks\",\n        \"merchantCapabilities\": \"applepay:merchantCapabilities\",\n        \"total\": \"schema:totalPrice\",\n        \"lineItems\": \"applepay:lineItems\",\n        \"shippingType\": \"applepay:shippingType\",\n        \"supportedCountries\": \"applepay:supportedCountries\"\n      }\n    },\n\n    \"LineItem\": {\n      \"@id\": \"applepay:LineItem\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"amount\": {\n          \"@id\"\
  : \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"type\": \"applepay:lineItemType\",\n        \"paymentTiming\": \"applepay:paymentTiming\"\n      }\n    },\n\n    \"PaymentToken\": {\n      \"@id\": \"applepay:PaymentToken\",\n      \"@context\": {\n        \"transactionIdentifier\": \"schema:identifier\",\n        \"paymentData\": \"applepay:paymentData\",\n        \"paymentMethod\": \"applepay:paymentMethod\"\n      }\n    },\n\n    \"PaymentData\": {\n      \"@id\": \"applepay:PaymentData\",\n      \"@context\": {\n        \"data\": \"applepay:encryptedData\",\n        \"signature\": \"applepay:signature\",\n        \"header\": \"applepay:header\",\n        \"version\": \"applepay:tokenVersion\"\n      }\n    },\n\n    \"PaymentDataHeader\": {\n      \"@id\": \"applepay:PaymentDataHeader\",\n      \"@context\": {\n        \"ephemeralPublicKey\": \"applepay:ephemeralPublicKey\",\n        \"wrappedKey\": \"applepay:wrappedKey\",\n        \"publicKeyHash\"\
  : \"applepay:publicKeyHash\",\n        \"transactionId\": \"schema:identifier\"\n      }\n    },\n\n    \"PaymentMethod\": {\n      \"@id\": \"applepay:PaymentMethod\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"network\": \"applepay:paymentNetwork\",\n        \"type\": \"applepay:cardType\"\n      }\n    },\n\n    \"PaymentContact\": {\n      \"@id\": \"applepay:PaymentContact\",\n      \"@context\": {\n        \"givenName\": \"schema:givenName\",\n        \"familyName\": \"schema:familyName\",\n        \"emailAddress\": \"schema:email\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"addressLines\": \"schema:streetAddress\",\n        \"locality\": \"schema:addressLocality\",\n        \"administrativeArea\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"countryCode\": \"applepay:countryCode\"\n      }\n    },\n\n    \"MerchantSession\": {\n      \"@id\"\
  : \"applepay:MerchantSession\",\n      \"@context\": {\n        \"merchantSessionIdentifier\": \"schema:identifier\",\n        \"merchantIdentifier\": \"applepay:merchantIdentifier\",\n        \"displayName\": \"schema:name\",\n        \"domainName\": \"applepay:domainName\",\n        \"epochTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nonce\": \"applepay:nonce\",\n        \"signature\": \"applepay:signature\"\n      }\n    },\n\n    \"ShippingMethod\": {\n      \"@id\": \"applepay:ShippingMethod\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"detail\": \"schema:description\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"identifier\": \"schema:identifier\"\n      }\n    },\n\n    \"DecryptedPaymentData\"\
  : {\n      \"@id\": \"applepay:DecryptedPaymentData\",\n      \"@context\": {\n        \"applicationPrimaryAccountNumber\": \"applepay:dpan\",\n        \"applicationExpirationDate\": \"applepay:dpanExpiration\",\n        \"currencyCode\": \"schema:priceCurrency\",\n        \"transactionAmount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"cardholderName\": \"schema:name\",\n        \"deviceManufacturerIdentifier\": \"applepay:deviceManufacturerIdentifier\",\n        \"paymentDataType\": \"applepay:paymentDataType\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apple-pay/refs/heads/main/json-ld/apple-pay-context.jsonld
tags:
- Apple
- Contactless Payments
- Digital Wallet
- E-Commerce
- Mobile Payments
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
