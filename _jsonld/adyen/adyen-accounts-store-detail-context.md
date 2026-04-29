---
class_count: 1
classes:
- StoreDetail
context_file: json-ld/adyen-accounts-store-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-store-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Store Detail from Adyen.
layout: jsonld
name: Adyen Accounts Store Detail Context
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
  name: address
  type: string
- container: ''
  name: fullPhoneNumber
  type: string
- container: ''
  name: logo
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: merchantCategoryCode
  type: string
- container: ''
  name: merchantHouseNumber
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: splitConfigurationUUID
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: store
  type: string
- container: ''
  name: storeName
  type: string
- container: ''
  name: storeReference
  type: string
- container: ''
  name: virtualAccount
  type: string
- container: ''
  name: webAddress
  type: string
property_count: 15
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-store-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoreDetail\": \"adyen:StoreDetail\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullPhoneNumber\": {\n      \"@id\": \"adyen:fullPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"adyen:logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantCategoryCode\": {\n      \"@id\": \"adyen:merchantCategoryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantHouseNumber\": {\n      \"@id\": \"adyen:merchantHouseNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"adyen:phoneNumber\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splitConfigurationUUID\": {\n      \"@id\": \"adyen:splitConfigurationUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeName\": {\n      \"@id\": \"adyen:storeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeReference\": {\n      \"@id\": \"adyen:storeReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualAccount\": {\n      \"@id\": \"adyen:virtualAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webAddress\": {\n      \"@id\": \"adyen:webAddress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-store-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
