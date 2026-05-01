---
api_specs:
- filename: fiscal-data-api-openapi.yml
  format: yaml
  label: Treasury Fiscal Data API
  slug: fiscal-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/refs/heads/main/openapi/fiscal-data-api-openapi.yml
- filename: ofac-sdn-api-openapi.yml
  format: yaml
  label: OFAC Sanctions List Service API
  slug: ofac-sanctions-list-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/refs/heads/main/openapi/ofac-sdn-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/treasury-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/refs/heads/main/json-ld/treasury-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Treasury from Department of the Treasury.
layout: jsonld
name: Treasury Context
namespaces:
- prefix: treas
  uri: https://api-evangelist.com/department-of-the-treasury/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DebtRecord
  type: ''
- container: ''
  name: OperatingCashBalance
  type: ''
- container: ''
  name: ExchangeRate
  type: ''
- container: ''
  name: SanctionedEntity
  type: ''
- container: ''
  name: SanctionsProgram
  type: ''
property_count: 5
provider_name: Department of the Treasury
provider_slug: department-of-the-treasury
slug: treasury-context
source_filename: treasury-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"treas\": \"https://api-evangelist.com/department-of-the-treasury/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DebtRecord\": {\n      \"@id\": \"treas:DebtRecord\",\n      \"@context\": {\n        \"record_date\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:date\" },\n        \"tot_pub_debt_out_amt\": { \"@id\": \"treas:totalPublicDebtOutstanding\", \"@type\": \"xsd:decimal\" },\n        \"debt_held_public_amt\": { \"@id\": \"treas:debtHeldByPublic\", \"@type\": \"xsd:decimal\" },\n        \"intragov_hold_amt\": { \"@id\": \"treas:intragovernmentalHoldings\", \"@type\": \"xsd:decimal\" }\n      }\n    },\n    \"OperatingCashBalance\": {\n      \"@id\": \"treas:OperatingCashBalance\",\n      \"@context\": {\n        \"record_date\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:date\" },\n        \"open_today_bal\"\
  : { \"@id\": \"treas:openingBalance\", \"@type\": \"xsd:decimal\" },\n        \"close_today_bal\": { \"@id\": \"treas:closingBalance\", \"@type\": \"xsd:decimal\" },\n        \"account_type\": \"treas:accountType\"\n      }\n    },\n    \"ExchangeRate\": {\n      \"@id\": \"treas:ExchangeRate\",\n      \"@context\": {\n        \"record_date\": { \"@id\": \"dcterms:date\", \"@type\": \"xsd:date\" },\n        \"country_currency_desc\": \"treas:currency\",\n        \"exchange_rate\": { \"@id\": \"treas:rate\", \"@type\": \"xsd:decimal\" }\n      }\n    },\n    \"SanctionedEntity\": {\n      \"@id\": \"treas:SanctionedEntity\",\n      \"@context\": {\n        \"uid\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"treas:entityType\",\n        \"programs\": \"treas:sanctionsProgram\",\n        \"nationalities\": \"schema:nationality\",\n        \"sanctionsListType\": \"treas:sanctionsListType\"\n      }\n    },\n    \"SanctionsProgram\": {\n      \"@id\": \"\
  treas:SanctionsProgram\",\n      \"@context\": {\n        \"code\": \"schema:identifier\",\n        \"description\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-the-treasury/refs/heads/main/json-ld/treasury-context.jsonld
tags:
- Federal Government
- Finance
- Debt
- Sanctions
- JSON-LD
- Linked Data
- Semantic Web
---
