---
class_count: 1
classes:
- Rebates
context_file: json-ld/adyen-terminal-rebates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-rebates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Rebates from Adyen.
layout: jsonld
name: Adyen Terminal Rebates Context
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
  name: TotalRebate
  type: decimal
- container: ''
  name: RebateLabel
  type: string
- container: set
  name: SaleItemRebate
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-rebates-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Rebates\": \"adyen:Rebates\",\n    \"TotalRebate\": {\n      \"@id\": \"adyen:TotalRebate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"RebateLabel\": {\n      \"@id\": \"adyen:RebateLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleItemRebate\": {\n      \"@id\": \"adyen:SaleItemRebate\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-rebates-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
