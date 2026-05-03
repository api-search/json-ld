---
class_count: 23
classes:
- TaxDocument
- documentType
- taxYear
- issuer
- recipient
- FormBox
- boxNumber
- boxAmount
- W2
- Form1099NEC
- Form1099INT
- Form1099DIV
- FormK1
- FATCA8938
- FBAR
- tin
- name
- address
- Organization
- Person
- MonetaryAmount
- currency
- value
context_file: json-ld/tax-templates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tax-templates/refs/heads/main/json-ld/tax-templates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tax Templates from Tax Templates.
layout: jsonld
name: Tax Templates Context
namespaces:
- prefix: tax
  uri: https://github.com/api-evangelist/tax-templates/vocab/
- prefix: irs
  uri: https://www.irs.gov/vocab/
- prefix: fatca
  uri: https://www.irs.gov/fatca/vocab/
properties: []
property_count: 0
provider_name: Tax Templates
provider_slug: tax-templates
slug: tax-templates-context
source_filename: tax-templates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tax\": \"https://github.com/api-evangelist/tax-templates/vocab/\",\n    \"irs\": \"https://www.irs.gov/vocab/\",\n    \"fatca\": \"https://www.irs.gov/fatca/vocab/\",\n    \"TaxDocument\": \"tax:TaxDocument\",\n    \"documentType\": \"tax:documentType\",\n    \"taxYear\": \"tax:taxYear\",\n    \"issuer\": \"tax:issuer\",\n    \"recipient\": \"tax:recipient\",\n    \"FormBox\": \"tax:FormBox\",\n    \"boxNumber\": \"tax:boxNumber\",\n    \"boxAmount\": \"tax:boxAmount\",\n    \"W2\": \"irs:FormW2\",\n    \"Form1099NEC\": \"irs:Form1099NEC\",\n    \"Form1099INT\": \"irs:Form1099INT\",\n    \"Form1099DIV\": \"irs:Form1099DIV\",\n    \"FormK1\": \"irs:FormK1\",\n    \"FATCA8938\": \"fatca:Form8938\",\n    \"FBAR\": \"fatca:FBAR\",\n    \"tin\": \"schema:taxID\",\n    \"name\": \"schema:name\",\n    \"address\": \"schema:address\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\"\
  ,\n    \"MonetaryAmount\": \"schema:MonetaryAmount\",\n    \"currency\": \"schema:currency\",\n    \"value\": \"schema:value\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tax-templates/refs/heads/main/json-ld/tax-templates-context.jsonld
tags:
- Documentation
- Finance
- Tax
- Templates
- Compliance
- JSON-LD
- Linked Data
- Semantic Web
---
