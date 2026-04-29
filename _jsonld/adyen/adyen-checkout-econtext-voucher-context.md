---
class_count: 1
classes:
- EcontextVoucherDetails
context_file: json-ld/adyen-checkout-econtext-voucher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-econtext-voucher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Econtext Voucher from Adyen.
layout: jsonld
name: Adyen Checkout Econtext Voucher Context
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
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: type
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-econtext-voucher-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EcontextVoucherDetails\": \"adyen:EcontextVoucherDetails\",\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-econtext-voucher-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
