---
class_count: 1
classes:
- TransactionTotals
context_file: json-ld/adyen-terminal-transaction-totals-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-transaction-totals-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Transaction Totals from Adyen.
layout: jsonld
name: Adyen Terminal Transaction Totals Context
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
  name: PaymentInstrumentType
  type: string
- container: ''
  name: AcquirerID
  type: integer
- container: ''
  name: HostReconciliationID
  type: string
- container: ''
  name: CardBrand
  type: string
- container: ''
  name: POIID
  type: string
- container: ''
  name: SaleID
  type: string
- container: ''
  name: OperatorID
  type: string
- container: ''
  name: ShiftNumber
  type: string
- container: ''
  name: TotalsGroupID
  type: string
- container: ''
  name: PaymentCurrency
  type: string
- container: set
  name: PaymentTotals
  type: string
- container: ''
  name: LoyaltyUnit
  type: string
- container: ''
  name: LoyaltyCurrency
  type: string
- container: set
  name: LoyaltyTotals
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-transaction-totals-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransactionTotals\": \"adyen:TransactionTotals\",\n    \"PaymentInstrumentType\": {\n      \"@id\": \"adyen:PaymentInstrumentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcquirerID\": {\n      \"@id\": \"adyen:AcquirerID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HostReconciliationID\": {\n      \"@id\": \"adyen:HostReconciliationID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardBrand\": {\n      \"@id\": \"adyen:CardBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIID\": {\n      \"@id\": \"adyen:POIID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleID\": {\n      \"@id\": \"adyen:SaleID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatorID\": {\n      \"@id\": \"adyen:OperatorID\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ShiftNumber\": {\n      \"@id\": \"adyen:ShiftNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalsGroupID\": {\n      \"@id\": \"adyen:TotalsGroupID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentCurrency\": {\n      \"@id\": \"adyen:PaymentCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentTotals\": {\n      \"@id\": \"adyen:PaymentTotals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyUnit\": {\n      \"@id\": \"adyen:LoyaltyUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyCurrency\": {\n      \"@id\": \"adyen:LoyaltyCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyTotals\": {\n      \"@id\": \"adyen:LoyaltyTotals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-transaction-totals-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
