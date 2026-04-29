---
class_count: 1
classes:
- AccountTransactionList
context_file: json-ld/adyen-funds-account-transaction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-account-transaction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Account Transaction from Adyen.
layout: jsonld
name: Adyen Funds Account Transaction Context
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
  name: accountCode
  type: string
- container: ''
  name: hasNextPage
  type: boolean
- container: set
  name: transactions
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-account-transaction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountTransactionList\": \"adyen:AccountTransactionList\",\n    \"accountCode\": {\n      \"@id\": \"adyen:accountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasNextPage\": {\n      \"@id\": \"adyen:hasNextPage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"transactions\": {\n      \"@id\": \"adyen:transactions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-account-transaction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
