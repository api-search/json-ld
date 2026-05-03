---
api_specs:
- filename: zendit-api.yml
  format: yaml
  label: Zendit API
  slug: zendit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml
class_count: 17
classes:
- Balance
- BrandList
- Brand
- EsimPlan
- OfferList
- Offer
- PhoneLookup
- Price
- PurchaseList
- Purchase
- RedemptionInstructions
- Refund
- ReportRequest
- Report
- TransactionList
- Transaction
- name
context_file: json-ld/zendit-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zendit Api from Zendit.
layout: jsonld
name: Zendit Api Context
namespaces:
- prefix: zendit
  uri: https://zendit.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: accountId
  type: string
- container: set
  name: list
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: logoUrl
  type: string
- container: set
  name: types
  type: string
- container: ''
  name: planId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: dataUsed
  type: decimal
- container: ''
  name: dataTotal
  type: decimal
- container: ''
  name: validUntil
  type: dateTime
- container: ''
  name: offerId
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: price
  type: string
- container: ''
  name: send
  type: string
- container: ''
  name: receive
  type: string
- container: ''
  name: msisdn
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: details
  type: reference
- container: ''
  name: deliveryType
  type: string
- container: ''
  name: instructions
  type: string
- container: ''
  name: termsAndConditions
  type: string
- container: ''
  name: refundId
  type: string
- container: ''
  name: dateFrom
  type: date
- container: ''
  name: dateTo
  type: date
- container: ''
  name: reportId
  type: string
- container: ''
  name: downloadUrl
  type: string
- container: set
  name: history
  type: string
- container: ''
  name: timestamp
  type: dateTime
property_count: 38
provider_name: Zendit
provider_slug: zendit
slug: zendit-api-context
source_filename: zendit-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zendit\": \"https://zendit.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Balance\": \"zendit:Balance\",\n    \"BrandList\": \"zendit:BrandList\",\n    \"Brand\": \"zendit:Brand\",\n    \"EsimPlan\": \"zendit:EsimPlan\",\n    \"OfferList\": \"zendit:OfferList\",\n    \"Offer\": \"zendit:Offer\",\n    \"PhoneLookup\": \"zendit:PhoneLookup\",\n    \"Price\": \"zendit:Price\",\n    \"PurchaseList\": \"zendit:PurchaseList\",\n    \"Purchase\": \"zendit:Purchase\",\n    \"RedemptionInstructions\": \"zendit:RedemptionInstructions\",\n    \"Refund\": \"zendit:Refund\",\n    \"ReportRequest\": \"zendit:ReportRequest\",\n    \"Report\": \"zendit:Report\",\n    \"TransactionList\": \"zendit:TransactionList\",\n    \"Transaction\": \"zendit:Transaction\",\n    \"amount\": {\n      \"@id\": \"zendit:amount\",\n      \"\
  @type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"zendit:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"zendit:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"list\": {\n      \"@id\": \"zendit:list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"zendit:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"zendit:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"zendit:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"zendit:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"country\": {\n      \"@id\": \"zendit:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logoUrl\": {\n      \"@id\": \"zendit:logoUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"types\": {\n      \"@id\": \"zendit:types\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planId\": {\n      \"@id\": \"zendit:planId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"zendit:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataUsed\": {\n      \"@id\": \"zendit:dataUsed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dataTotal\": {\n      \"@id\": \"zendit:dataTotal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"validUntil\": {\n      \"@id\": \"zendit:validUntil\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"offerId\": {\n      \"@id\": \"zendit:offerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"zendit:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"zendit:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"zendit:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"zendit:price\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"send\": {\n      \"@id\": \"zendit:send\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receive\": {\n      \"@id\": \"zendit:receive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"msisdn\": {\n      \"@id\": \"zendit:msisdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"zendit:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"zendit:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"zendit:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"details\": {\n      \"@id\": \"zendit:details\",\n      \"@type\": \"@id\"\n    },\n    \"deliveryType\": {\n      \"@id\": \"zendit:deliveryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instructions\": {\n      \"@id\": \"zendit:instructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"termsAndConditions\": {\n      \"@id\": \"zendit:termsAndConditions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"refundId\": {\n      \"@id\": \"zendit:refundId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateFrom\": {\n      \"@id\": \"zendit:dateFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateTo\": {\n      \"@id\": \"zendit:dateTo\",\n      \"@type\": \"xsd:date\"\n    },\n    \"reportId\": {\n      \"@id\": \"zendit:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"zendit:downloadUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"history\": {\n      \"@id\": \"zendit:history\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"zendit:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-context.jsonld
tags:
- eSIM
- Gift Cards
- Mobile Top-Up
- Payments
- Prepaid
- JSON-LD
- Linked Data
- Semantic Web
---
