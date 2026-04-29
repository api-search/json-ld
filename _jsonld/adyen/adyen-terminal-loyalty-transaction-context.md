---
class_count: 2
classes:
- LoyaltyTransaction
- LoyaltyTransactionType
context_file: json-ld/adyen-terminal-loyalty-transaction-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-transaction-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Transaction from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Transaction Context
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
  name: Currency
  type: string
- container: ''
  name: TotalAmount
  type: decimal
- container: ''
  name: OriginalPOITransaction
  type: string
- container: ''
  name: TransactionConditions
  type: string
- container: set
  name: SaleItem
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-transaction-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyTransaction\": \"adyen:LoyaltyTransaction\",\n    \"LoyaltyTransactionType\": \"adyen:LoyaltyTransactionType\",\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalAmount\": {\n      \"@id\": \"adyen:TotalAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"OriginalPOITransaction\": {\n      \"@id\": \"adyen:OriginalPOITransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransactionConditions\": {\n      \"@id\": \"adyen:TransactionConditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleItem\": {\n      \"@id\": \"adyen:SaleItem\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-transaction-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
