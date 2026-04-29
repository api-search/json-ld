---
api_specs:
- filename: apptio-openapi.yaml
  format: yaml
  label: Apptio API
  slug: apptio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apptio/refs/heads/main/openapi/apptio-openapi.yaml
class_count: 15
classes:
- allocationId
- costCenter
- category
- period
- amount
- currency
- vendor
- tags
- budgetId
- name
- fiscalYear
- totalBudget
- spentAmount
- reportId
- status
context_file: json-ld/apptio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apptio/refs/heads/main/json-ld/apptio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apptio from Apptio.
layout: jsonld
name: Apptio Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: apptio
  uri: https://www.apptio.com/vocab#
properties: []
property_count: 0
provider_name: Apptio
provider_slug: apptio
slug: apptio-context
source_filename: apptio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"apptio\": \"https://www.apptio.com/vocab#\",\n    \"allocationId\": \"schema:identifier\",\n    \"costCenter\": \"apptio:costCenter\",\n    \"category\": \"schema:category\",\n    \"period\": \"apptio:period\",\n    \"amount\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"vendor\": \"schema:provider\",\n    \"tags\": \"apptio:tags\",\n    \"budgetId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"fiscalYear\": \"apptio:fiscalYear\",\n    \"totalBudget\": \"apptio:totalBudget\",\n    \"spentAmount\": \"apptio:spentAmount\",\n    \"reportId\": \"schema:identifier\",\n    \"status\": \"apptio:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apptio/refs/heads/main/json-ld/apptio-context.jsonld
tags:
- Analytics
- Cost Management
- IT Finance
- Technology Business Management
- JSON-LD
- Linked Data
- Semantic Web
---
