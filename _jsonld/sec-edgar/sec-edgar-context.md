---
api_specs:
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR Full-Text Search API
  slug: sec-edgar-full-text-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR Submissions API
  slug: sec-edgar-submissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR XBRL Company Facts API
  slug: sec-edgar-xbrl-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
class_count: 29
classes:
- Company
- Filing
- FinancialReport
- Person
- cik
- name
- tickers
- exchanges
- sic
- sicDescription
- ein
- fiscalYearEnd
- addresses
- stateOfIncorporation
- accessionNumber
- formType
- size
- isXBRL
- primaryDocument
- documents
- taxonomy
- concept
- fiscalYear
- fiscalPeriod
- val
- street1
- city
- stateOrCountry
- zipCode
context_file: json-ld/sec-edgar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/json-ld/sec-edgar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sec Edgar from sec-edgar.
layout: jsonld
name: Sec Edgar Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: edgar
  uri: https://data.sec.gov/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: xbrl
  uri: https://xbrl.org/2003/instance/
properties:
- container: ''
  name: website
  type: reference
- container: ''
  name: filingDate
  type: date
- container: ''
  name: reportDate
  type: date
- container: ''
  name: acceptanceDateTime
  type: dateTime
- container: ''
  name: end
  type: date
- container: ''
  name: start
  type: date
property_count: 6
provider_name: sec-edgar
provider_slug: sec-edgar
slug: sec-edgar-context
source_filename: sec-edgar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"edgar\": \"https://data.sec.gov/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"xbrl\": \"https://xbrl.org/2003/instance/\",\n\n    \"Company\": \"schema:Organization\",\n    \"Filing\": \"schema:CreativeWork\",\n    \"FinancialReport\": \"schema:FinancialProduct\",\n    \"Person\": \"schema:Person\",\n\n    \"cik\": \"edgar:cik\",\n    \"name\": \"schema:name\",\n    \"tickers\": \"edgar:tickerSymbol\",\n    \"exchanges\": \"edgar:listedExchange\",\n    \"sic\": \"edgar:sicCode\",\n    \"sicDescription\": \"edgar:sicDescription\",\n    \"ein\": \"schema:taxID\",\n    \"fiscalYearEnd\": \"edgar:fiscalYearEnd\",\n    \"website\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"addresses\": \"schema:address\",\n    \"stateOfIncorporation\": \"schema:addressRegion\",\n\n    \"accessionNumber\": \"edgar:accessionNumber\",\n    \"formType\"\
  : \"edgar:formType\",\n    \"filingDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"reportDate\": {\n      \"@id\": \"edgar:periodOfReport\",\n      \"@type\": \"xsd:date\"\n    },\n    \"acceptanceDateTime\": {\n      \"@id\": \"edgar:acceptanceDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size\": \"schema:fileSize\",\n    \"isXBRL\": \"edgar:isXBRL\",\n    \"primaryDocument\": \"schema:url\",\n    \"documents\": \"schema:hasPart\",\n\n    \"taxonomy\": \"xbrl:taxonomy\",\n    \"concept\": \"xbrl:concept\",\n    \"fiscalYear\": \"edgar:fiscalYear\",\n    \"fiscalPeriod\": \"edgar:fiscalPeriod\",\n    \"val\": \"edgar:reportedValue\",\n    \"end\": {\n      \"@id\": \"edgar:periodEnd\",\n      \"@type\": \"xsd:date\"\n    },\n    \"start\": {\n      \"@id\": \"edgar:periodStart\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"street1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"stateOrCountry\"\
  : \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/json-ld/sec-edgar-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
