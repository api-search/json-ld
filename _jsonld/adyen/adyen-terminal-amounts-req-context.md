---
class_count: 1
classes:
- AmountsReq
context_file: json-ld/adyen-terminal-amounts-req-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-amounts-req-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Amounts Req from Adyen.
layout: jsonld
name: Adyen Terminal Amounts Req Context
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
  name: RequestedAmount
  type: decimal
- container: ''
  name: CashBackAmount
  type: decimal
- container: ''
  name: TipAmount
  type: decimal
- container: ''
  name: PaidAmount
  type: decimal
- container: ''
  name: MinimumAmountToDeliver
  type: decimal
- container: ''
  name: MaximumCashBackAmount
  type: decimal
- container: ''
  name: MinimumSplitAmount
  type: decimal
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-amounts-req-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AmountsReq\": \"adyen:AmountsReq\",\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestedAmount\": {\n      \"@id\": \"adyen:RequestedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CashBackAmount\": {\n      \"@id\": \"adyen:CashBackAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TipAmount\": {\n      \"@id\": \"adyen:TipAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PaidAmount\": {\n      \"@id\": \"adyen:PaidAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MinimumAmountToDeliver\": {\n      \"@id\": \"adyen:MinimumAmountToDeliver\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MaximumCashBackAmount\": {\n      \"@id\": \"\
  adyen:MaximumCashBackAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MinimumSplitAmount\": {\n      \"@id\": \"adyen:MinimumSplitAmount\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-amounts-req-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
