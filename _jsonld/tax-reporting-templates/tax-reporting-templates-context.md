---
class_count: 27
classes:
- TaxReport
- reportType
- taxYear
- filingStatus
- filer
- tin
- tinType
- MeF
- Form1040
- Form1120
- FormW2
- Form1099NEC
- Form941
- income
- wages
- deductions
- taxLiability
- refund
- balanceDue
- effectiveTaxRate
- standardDeduction
- itemizedDeductions
- Person
- Organization
- address
- name
- taxID
context_file: json-ld/tax-reporting-templates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tax-reporting-templates/refs/heads/main/json-ld/tax-reporting-templates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tax Reporting Templates from Tax Reporting Templates.
layout: jsonld
name: Tax Reporting Templates Context
namespaces:
- prefix: tax
  uri: https://github.com/api-evangelist/tax-reporting-templates/vocab/
- prefix: irs
  uri: https://www.irs.gov/vocab/
properties: []
property_count: 0
provider_name: Tax Reporting Templates
provider_slug: tax-reporting-templates
slug: tax-reporting-templates-context
source_filename: tax-reporting-templates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tax\": \"https://github.com/api-evangelist/tax-reporting-templates/vocab/\",\n    \"irs\": \"https://www.irs.gov/vocab/\",\n    \"TaxReport\": \"tax:TaxReport\",\n    \"reportType\": \"tax:reportType\",\n    \"taxYear\": \"tax:taxYear\",\n    \"filingStatus\": \"tax:filingStatus\",\n    \"filer\": \"tax:filer\",\n    \"tin\": \"tax:taxpayerIdentificationNumber\",\n    \"tinType\": \"tax:tinType\",\n    \"MeF\": \"irs:ModernizedEFile\",\n    \"Form1040\": \"irs:Form1040\",\n    \"Form1120\": \"irs:Form1120\",\n    \"FormW2\": \"irs:FormW2\",\n    \"Form1099NEC\": \"irs:Form1099NEC\",\n    \"Form941\": \"irs:Form941\",\n    \"income\": \"schema:MonetaryAmount\",\n    \"wages\": \"tax:wages\",\n    \"deductions\": \"tax:deductions\",\n    \"taxLiability\": \"tax:taxLiability\",\n    \"refund\": \"tax:refund\",\n    \"balanceDue\": \"tax:balanceDue\",\n    \"effectiveTaxRate\": \"tax:effectiveTaxRate\",\n   \
  \ \"standardDeduction\": \"tax:standardDeduction\",\n    \"itemizedDeductions\": \"tax:itemizedDeductions\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n    \"address\": \"schema:address\",\n    \"name\": \"schema:name\",\n    \"taxID\": \"schema:taxID\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tax-reporting-templates/refs/heads/main/json-ld/tax-reporting-templates-context.jsonld
tags:
- Compliance
- Documentation
- Finance
- Reporting
- Tax
- Templates
- JSON-LD
- Linked Data
- Semantic Web
---
