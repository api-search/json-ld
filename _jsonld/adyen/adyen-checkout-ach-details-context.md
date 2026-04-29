---
class_count: 1
classes:
- AchDetails
context_file: json-ld/adyen-checkout-ach-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-ach-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Ach Details from Adyen.
layout: jsonld
name: Adyen Checkout Ach Details Context
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
  name: bankAccountNumber
  type: string
- container: ''
  name: bankAccountType
  type: string
- container: ''
  name: bankLocationId
  type: string
- container: ''
  name: checkoutAttemptId
  type: string
- container: ''
  name: encryptedBankAccountNumber
  type: string
- container: ''
  name: encryptedBankLocationId
  type: string
- container: ''
  name: ownerName
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
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-ach-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AchDetails\": \"adyen:AchDetails\",\n    \"bankAccountNumber\": {\n      \"@id\": \"adyen:bankAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountType\": {\n      \"@id\": \"adyen:bankAccountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankLocationId\": {\n      \"@id\": \"adyen:bankLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkoutAttemptId\": {\n      \"@id\": \"adyen:checkoutAttemptId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedBankAccountNumber\": {\n      \"@id\": \"adyen:encryptedBankAccountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptedBankLocationId\": {\n      \"@id\": \"adyen:encryptedBankLocationId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ownerName\": {\n      \"@id\": \"adyen:ownerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedPaymentMethodId\": {\n      \"@id\": \"adyen:storedPaymentMethodId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-ach-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
