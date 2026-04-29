---
class_count: 2
classes:
- CustomerOrderReq
- CustomerOrder
context_file: json-ld/adyen-terminal-customer-order-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-customer-order-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Customer Order from Adyen.
layout: jsonld
name: Adyen Terminal Customer Order Context
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
  name: CustomerOrderID
  type: string
- container: ''
  name: SaleReferenceID
  type: string
- container: ''
  name: OpenOrderState
  type: boolean
- container: ''
  name: StartDate
  type: dateTime
- container: ''
  name: EndDate
  type: dateTime
- container: ''
  name: ForecastedAmount
  type: decimal
- container: ''
  name: CurrentAmount
  type: decimal
- container: ''
  name: Currency
  type: string
- container: ''
  name: AccessedBy
  type: string
- container: ''
  name: AdditionalInformation
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-customer-order-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomerOrderReq\": \"adyen:CustomerOrderReq\",\n    \"CustomerOrder\": \"adyen:CustomerOrder\",\n    \"CustomerOrderID\": {\n      \"@id\": \"adyen:CustomerOrderID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleReferenceID\": {\n      \"@id\": \"adyen:SaleReferenceID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenOrderState\": {\n      \"@id\": \"adyen:OpenOrderState\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"StartDate\": {\n      \"@id\": \"adyen:StartDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndDate\": {\n      \"@id\": \"adyen:EndDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ForecastedAmount\": {\n      \"@id\": \"adyen:ForecastedAmount\",\n      \"@type\": \"xsd:decimal\"\n\
  \    },\n    \"CurrentAmount\": {\n      \"@id\": \"adyen:CurrentAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessedBy\": {\n      \"@id\": \"adyen:AccessedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdditionalInformation\": {\n      \"@id\": \"adyen:AdditionalInformation\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-customer-order-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
