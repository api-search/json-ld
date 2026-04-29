---
class_count: 4
classes:
- AccountHolderBalanceRequest
- AccountHolderBalanceResponse
- AccountHolderTransactionListRequest
- AccountHolderTransactionListResponse
context_file: json-ld/adyen-funds-account-holder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-account-holder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Account Holder from Adyen.
layout: jsonld
name: Adyen Funds Account Holder Context
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
  name: accountHolderCode
  type: string
- container: set
  name: balancePerAccount
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
- container: ''
  name: totalBalance
  type: string
- container: set
  name: transactionListsPerAccount
  type: string
- container: set
  name: transactionStatuses
  type: string
- container: set
  name: accountTransactionLists
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-account-holder-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountHolderBalanceRequest\": \"adyen:AccountHolderBalanceRequest\",\n    \"AccountHolderBalanceResponse\": \"adyen:AccountHolderBalanceResponse\",\n    \"AccountHolderTransactionListRequest\": \"adyen:AccountHolderTransactionListRequest\",\n    \"AccountHolderTransactionListResponse\": \"adyen:AccountHolderTransactionListResponse\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancePerAccount\": {\n      \"@id\": \"adyen:balancePerAccount\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalBalance\": {\n      \"@id\": \"adyen:totalBalance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionListsPerAccount\": {\n      \"@id\": \"adyen:transactionListsPerAccount\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionStatuses\": {\n      \"@id\": \"adyen:transactionStatuses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountTransactionLists\": {\n      \"@id\": \"adyen:accountTransactionLists\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-account-holder-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
