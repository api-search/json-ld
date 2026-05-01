---
api_specs:
- filename: finout-api-openapi.yml
  format: yaml
  label: Finout
  slug: finout
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/finout/refs/heads/main/openapi/finout-api-openapi.yml
class_count: 2
classes:
- name
- description
context_file: json-ld/finout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/finout/refs/heads/main/json-ld/finout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Finout from Finout.
layout: jsonld
name: Finout Context
namespaces:
- prefix: finout
  uri: https://app.finout.io/v1/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: viewId
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: scanId
  type: string
- container: ''
  name: scanName
  type: string
- container: ''
  name: scanLastRunTime
  type: dateTime
- container: ''
  name: scanTotalCost
  type: double
- container: ''
  name: scanTotalWaste
  type: double
- container: ''
  name: scanYearlyPotentialSavings
  type: double
- container: ''
  name: lastRunTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: costCenter
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: rules
  type: '@json'
- container: ''
  name: filter
  type: '@json'
- container: ''
  name: configuration
  type: '@json'
- container: ''
  name: unixTimeMillSecondsStart
  type: integer
- container: ''
  name: unixTimeMillSecondsEnd
  type: integer
- container: ''
  name: requestId
  type: string
- container: ''
  name: groupBy
  type: string
property_count: 19
provider_name: Finout
provider_slug: finout
slug: finout-context
source_filename: finout-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"finout\": \"https://app.finout.io/v1/\",\n    \"viewId\": {\n      \"@id\": \"finout:viewId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"finout:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanId\": {\n      \"@id\": \"finout:scanId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanName\": {\n      \"@id\": \"finout:scanName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanLastRunTime\": {\n      \"@id\": \"finout:scanLastRunTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"scanTotalCost\": {\n      \"@id\": \"finout:scanTotalCost\",\n      \"@type\": \"xsd:double\"\n    },\n    \"scanTotalWaste\": {\n      \"@id\": \"finout:scanTotalWaste\",\n      \"@type\": \"xsd:double\"\n    },\n    \"scanYearlyPotentialSavings\": {\n      \"@id\": \"finout:scanYearlyPotentialSavings\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lastRunTime\"\
  : {\n      \"@id\": \"finout:lastRunTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"finout:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"costCenter\": {\n      \"@id\": \"finout:costCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"finout:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"finout:rules\",\n      \"@type\": \"@json\"\n    },\n    \"filter\": {\n      \"@id\": \"finout:filter\",\n      \"@type\": \"@json\"\n    },\n    \"configuration\": {\n      \"@id\": \"finout:configuration\",\n      \"@type\": \"@json\"\n    },\n    \"unixTimeMillSecondsStart\": {\n      \"@id\": \"finout:unixTimeMillSecondsStart\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unixTimeMillSecondsEnd\": {\n      \"@id\": \"finout:unixTimeMillSecondsEnd\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requestId\": {\n      \"@id\": \"finout:requestId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"groupBy\": {\n      \"@id\": \"finout:groupBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/finout/refs/heads/main/json-ld/finout-context.jsonld
tags:
- Budgets
- Costs
- FinOps
- JSON-LD
- Linked Data
- Semantic Web
---
