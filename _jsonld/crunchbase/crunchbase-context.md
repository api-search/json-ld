---
api_specs:
- filename: crunchbase-openapi.yml
  format: yaml
  label: Crunchbase API
  slug: crunchbase-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/openapi/crunchbase-openapi.yml
class_count: 18
classes:
- Organization
- Person
- FundingRound
- Acquisition
- Ipo
- name
- short_description
- category_groups
- location_identifiers
- funding_total
- money_raised
- investment_type
- lead_investor_identifiers
- acquirer_identifier
- acquiree_identifier
- first_name
- last_name
- primary_job_title
context_file: json-ld/crunchbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/json-ld/crunchbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Crunchbase from Crunchbase.
layout: jsonld
name: Crunchbase Context
namespaces:
- prefix: cb
  uri: https://data.crunchbase.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: uuid
  type: string
- container: ''
  name: permalink
  type: ''
- container: ''
  name: website_url
  type: anyURI
- container: ''
  name: founded_on
  type: date
- container: ''
  name: closed_on
  type: date
- container: ''
  name: announced_on
  type: date
- container: ''
  name: stock_symbol
  type: ''
- container: ''
  name: went_public_on
  type: date
- container: ''
  name: primary_organization
  type: reference
property_count: 9
provider_name: Crunchbase
provider_slug: crunchbase
slug: crunchbase-context
source_filename: crunchbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cb\": \"https://data.crunchbase.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n    \"FundingRound\": \"cb:FundingRound\",\n    \"Acquisition\": \"cb:Acquisition\",\n    \"Ipo\": \"cb:Ipo\",\n    \"uuid\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"permalink\": {\"@id\": \"schema:url\"},\n    \"name\": \"schema:name\",\n    \"short_description\": \"schema:description\",\n    \"website_url\": {\"@id\": \"schema:url\", \"@type\": \"xsd:anyURI\"},\n    \"founded_on\": {\"@id\": \"schema:foundingDate\", \"@type\": \"xsd:date\"},\n    \"closed_on\": {\"@id\": \"schema:dissolutionDate\", \"@type\": \"xsd:date\"},\n    \"category_groups\": \"schema:industry\",\n    \"location_identifiers\": \"schema:location\",\n    \"funding_total\": \"cb:fundingTotal\",\n    \"\
  money_raised\": \"cb:moneyRaised\",\n    \"investment_type\": \"cb:investmentType\",\n    \"announced_on\": {\"@id\": \"schema:datePublished\", \"@type\": \"xsd:date\"},\n    \"lead_investor_identifiers\": \"cb:leadInvestor\",\n    \"acquirer_identifier\": \"cb:acquirer\",\n    \"acquiree_identifier\": \"cb:acquiree\",\n    \"stock_symbol\": {\"@id\": \"schema:tickerSymbol\"},\n    \"went_public_on\": {\"@id\": \"cb:wentPublicOn\", \"@type\": \"xsd:date\"},\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"primary_organization\": {\"@id\": \"schema:worksFor\", \"@type\": \"@id\"},\n    \"primary_job_title\": \"schema:jobTitle\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/json-ld/crunchbase-context.jsonld
tags:
- Business Data
- Funding
- Investments
- Startups
- Private Markets
- Firmographics
- JSON-LD
- Linked Data
- Semantic Web
---
