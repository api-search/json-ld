---
class_count: 1
classes:
- TotalFilter
context_file: json-ld/adyen-terminal-total-filter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-total-filter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Total Filter from Adyen.
layout: jsonld
name: Adyen Terminal Total Filter Context
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
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-total-filter-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TotalFilter\": \"adyen:TotalFilter\",\n    \"POIID\": {\n      \"@id\": \"adyen:POIID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleID\": {\n      \"@id\": \"adyen:SaleID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatorID\": {\n      \"@id\": \"adyen:OperatorID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShiftNumber\": {\n      \"@id\": \"adyen:ShiftNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalsGroupID\": {\n      \"@id\": \"adyen:TotalsGroupID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-total-filter-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
