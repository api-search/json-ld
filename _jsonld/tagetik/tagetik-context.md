---
api_specs:
- filename: cch-tagetik-odata-openapi.yml
  format: yaml
  label: CCH Tagetik OData API
  slug: cch-tagetik-odata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/openapi/cch-tagetik-odata-openapi.yml
class_count: 3
classes:
- FinancialRecord
- FinancialModel
- AnalyticalWorkspace
context_file: json-ld/tagetik-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/json-ld/tagetik-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tagetik from CCH Tagetik.
layout: jsonld
name: Tagetik Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tagetik
  uri: https://tagetik.com/vocab/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Year
  type: integer
- container: ''
  name: Period
  type: string
- container: ''
  name: Account
  type: string
- container: ''
  name: AccountDescription
  type: ''
- container: ''
  name: Entity
  type: string
- container: ''
  name: EntityDescription
  type: ''
- container: ''
  name: Currency
  type: string
- container: ''
  name: Amount
  type: decimal
- container: ''
  name: AmountLC
  type: decimal
- container: ''
  name: Scenario
  type: string
- container: ''
  name: DataType
  type: string
- container: ''
  name: Flow
  type: string
- container: ''
  name: Interco
  type: string
- container: ''
  name: Dimension1
  type: string
- container: ''
  name: Dimension2
  type: string
- container: ''
  name: Dimension3
  type: string
- container: ''
  name: ConsolidationStatus
  type: string
- container: ''
  name: AuditTrail
  type: string
- container: ''
  name: database
  type: string
- container: ''
  name: analyticalWorkspace
  type: string
property_count: 20
provider_name: CCH Tagetik
provider_slug: tagetik
slug: tagetik-context
source_filename: tagetik-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tagetik\": \"https://tagetik.com/vocab/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FinancialRecord\": \"tagetik:FinancialRecord\",\n    \"FinancialModel\": \"tagetik:FinancialModel\",\n    \"AnalyticalWorkspace\": \"tagetik:AnalyticalWorkspace\",\n\n    \"Year\": { \"@id\": \"tagetik:fiscalYear\", \"@type\": \"xsd:integer\" },\n    \"Period\": { \"@id\": \"tagetik:reportingPeriod\", \"@type\": \"xsd:string\" },\n    \"Account\": { \"@id\": \"tagetik:accountCode\", \"@type\": \"xsd:string\" },\n    \"AccountDescription\": { \"@id\": \"schema:name\" },\n    \"Entity\": { \"@id\": \"tagetik:entityCode\", \"@type\": \"xsd:string\" },\n    \"EntityDescription\": { \"@id\": \"schema:legalName\" },\n    \"Currency\": { \"@id\": \"schema:currency\", \"@type\": \"xsd:string\" },\n    \"Amount\": { \"@id\":\
  \ \"tagetik:amount\", \"@type\": \"xsd:decimal\" },\n    \"AmountLC\": { \"@id\": \"tagetik:amountLocalCurrency\", \"@type\": \"xsd:decimal\" },\n    \"Scenario\": { \"@id\": \"tagetik:scenario\", \"@type\": \"xsd:string\" },\n    \"DataType\": { \"@id\": \"tagetik:dataType\", \"@type\": \"xsd:string\" },\n    \"Flow\": { \"@id\": \"tagetik:cashFlowType\", \"@type\": \"xsd:string\" },\n    \"Interco\": { \"@id\": \"tagetik:intercompanyPartner\", \"@type\": \"xsd:string\" },\n    \"Dimension1\": { \"@id\": \"tagetik:dimension1\", \"@type\": \"xsd:string\" },\n    \"Dimension2\": { \"@id\": \"tagetik:dimension2\", \"@type\": \"xsd:string\" },\n    \"Dimension3\": { \"@id\": \"tagetik:dimension3\", \"@type\": \"xsd:string\" },\n    \"ConsolidationStatus\": { \"@id\": \"tagetik:consolidationStatus\", \"@type\": \"xsd:string\" },\n    \"AuditTrail\": { \"@id\": \"tagetik:auditTrail\", \"@type\": \"xsd:string\" },\n    \"database\": { \"@id\": \"tagetik:database\", \"@type\": \"xsd:string\"\
  \ },\n    \"analyticalWorkspace\": { \"@id\": \"tagetik:analyticalWorkspace\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/json-ld/tagetik-context.jsonld
tags:
- Analytics
- Budgeting
- Corporate Performance Management
- ESG
- Financial Close
- Financial Consolidation
- Financial Planning
- OData
- Reporting
- JSON-LD
- Linked Data
- Semantic Web
---
