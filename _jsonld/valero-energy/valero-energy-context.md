---
class_count: 0
classes: []
context_file: json-ld/valero-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/json-ld/valero-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Valero Energy from Valero Energy.
layout: jsonld
name: Valero Energy Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: energy
  uri: https://schema.org/Energy
properties:
- container: ''
  name: Refinery
  type: ''
- container: ''
  name: FinancialResult
  type: ''
- container: ''
  name: Organization
  type: ''
property_count: 3
provider_name: Valero Energy
provider_slug: valero-energy
slug: valero-energy-context
source_filename: valero-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api-evangelist.com/vocab/valero-energy#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"energy\": \"https://schema.org/Energy\",\n    \"Refinery\": {\n      \"@id\": \"schema:LocalBusiness\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"location\": \"schema:location\",\n        \"capacity_bpd\": \"schema:additionalProperty\",\n        \"type\": \"@type\",\n        \"products\": \"schema:produces\",\n        \"operational\": \"schema:isAccessibleForFree\"\n      }\n    },\n    \"FinancialResult\": {\n      \"@id\": \"schema:FinancialProduct\",\n      \"@context\": {\n        \"revenue\": \"schema:totalPaymentDue\",\n        \"net_income\": \"schema:profit\",\n        \"earnings_per_share\": \"schema:price\",\n        \"dividend_per_share\": \"schema:annualPercentageRate\",\n        \"reported_date\": \"schema:datePublished\"\n      }\n    },\n    \"Organization\"\
  : {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"ticker\": \"schema:tickerSymbol\",\n        \"exchange\": \"schema:exchangeTicker\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/json-ld/valero-energy-context.jsonld
tags:
- Energy
- Petroleum
- Refining
- Renewable Fuels
- Fortune 100
- Ethanol
- Renewable Diesel
- JSON-LD
- Linked Data
- Semantic Web
---
