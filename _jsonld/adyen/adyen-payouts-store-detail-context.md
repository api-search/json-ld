---
class_count: 4
classes:
- StoreDetailAndSubmitRequest
- StoreDetailAndSubmitResponse
- StoreDetailRequest
- StoreDetailResponse
context_file: json-ld/adyen-payouts-store-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-store-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Store Detail from Adyen.
layout: jsonld
name: Adyen Payouts Store Detail Context
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
  name: additionalData
  type: reference
- container: ''
  name: amount
  type: string
- container: ''
  name: bank
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: card
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: entityType
  type: string
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: selectedBrand
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
  name: shopperStatement
  type: string
- container: ''
  name: socialSecurityNumber
  type: string
- container: ''
  name: telephoneNumber
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: refusalReason
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: recurringDetailReference
  type: string
property_count: 23
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-store-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoreDetailAndSubmitRequest\": \"adyen:StoreDetailAndSubmitRequest\",\n    \"StoreDetailAndSubmitResponse\": \"adyen:StoreDetailAndSubmitResponse\",\n    \"StoreDetailRequest\": \"adyen:StoreDetailRequest\",\n    \"StoreDetailResponse\": \"adyen:StoreDetailResponse\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bank\": {\n      \"@id\": \"adyen:bank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedBrand\": {\n      \"@id\": \"adyen:selectedBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refusalReason\": {\n      \"@id\": \"adyen:refusalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-store-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
