---
api_specs:
- filename: charityapi-openapi.yml
  format: yaml
  label: CharityAPI
  slug: charityapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charityapi/refs/heads/main/openapi/charityapi-openapi.yml
class_count: 0
classes: []
context_file: json-ld/charityapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/charityapi/refs/heads/main/json-ld/charityapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Charityapi from CharityAPI.
layout: jsonld
name: Charityapi Context
namespaces:
- prefix: charityapi
  uri: https://charityapi.org/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: PublicCharityCheck
  type: ''
property_count: 2
provider_name: CharityAPI
provider_slug: charityapi
slug: charityapi-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"charityapi\": \"https://charityapi.org/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"schema:NGO\",\n      \"@context\": {\n        \"ein\": \"charityapi:ein\",\n        \"name\": \"schema:legalName\",\n        \"ico\": \"charityapi:inCareOf\",\n        \"street\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\",\n        \"subsection\": \"charityapi:irsSubsection\",\n        \"classification\": \"charityapi:irsClassification\",\n        \"ruling\": {\n          \"@id\": \"charityapi:irsRuling\",\n          \"@type\": \"xsd:date\"\n        },\n        \"deductibility\": \"charityapi:deductibility\",\n        \"foundation\": \"charityapi:foundationCode\",\n      \
  \  \"activity\": \"charityapi:activityCode\",\n        \"status\": \"charityapi:taxExemptStatus\",\n        \"tax_period\": \"charityapi:taxPeriod\",\n        \"asset_amt\": {\n          \"@id\": \"charityapi:totalAssets\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"income_amt\": {\n          \"@id\": \"charityapi:totalIncome\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"revenue_amt\": {\n          \"@id\": \"charityapi:totalRevenue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ntee_cd\": \"charityapi:nteeCode\"\n      }\n    },\n\n    \"PublicCharityCheck\": {\n      \"@id\": \"charityapi:PublicCharityCheck\",\n      \"@context\": {\n        \"ein\": \"charityapi:ein\",\n        \"public_charity\": {\n          \"@id\": \"charityapi:isPublicCharity\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/charityapi/refs/heads/main/json-ld/charityapi-context.jsonld
tags:
- 501c3
- Charities
- Donations
- EIN
- IRS
- Non-Profits
- Tax Compliance
- Verification
- JSON-LD
- Linked Data
- Semantic Web
---
