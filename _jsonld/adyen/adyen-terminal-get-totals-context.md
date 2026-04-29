---
class_count: 2
classes:
- GetTotalsRequest
- GetTotalsResponse
context_file: json-ld/adyen-terminal-get-totals-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-get-totals-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Get Totals from Adyen.
layout: jsonld
name: Adyen Terminal Get Totals Context
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
  name: TotalDetails
  type: string
- container: ''
  name: TotalFilter
  type: string
- container: ''
  name: Response
  type: string
- container: ''
  name: POIReconciliationID
  type: integer
- container: set
  name: TransactionTotals
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-get-totals-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetTotalsRequest\": \"adyen:GetTotalsRequest\",\n    \"GetTotalsResponse\": \"adyen:GetTotalsResponse\",\n    \"TotalDetails\": {\n      \"@id\": \"adyen:TotalDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalFilter\": {\n      \"@id\": \"adyen:TotalFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIReconciliationID\": {\n      \"@id\": \"adyen:POIReconciliationID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TransactionTotals\": {\n      \"@id\": \"adyen:TransactionTotals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-get-totals-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
