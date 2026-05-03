---
api_specs:
- filename: us-senate-lda-openapi.yml
  format: yaml
  label: Senate Lobbying Disclosure Act (LDA) API
  slug: lda-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/openapi/us-senate-lda-openapi.yml
class_count: 4
classes:
- LDAFiling
- Registrant
- Client
- Lobbyist
context_file: json-ld/us-senate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/json-ld/us-senate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Senate from US Senate.
layout: jsonld
name: Us Senate Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: lda
  uri: https://lda.senate.gov/vocab/
- prefix: org
  uri: http://www.w3.org/ns/org#
properties:
- container: ''
  name: filing_uuid
  type: string
- container: ''
  name: filing_type
  type: string
- container: ''
  name: filing_year
  type: integer
- container: ''
  name: filing_period
  type: string
- container: ''
  name: income
  type: decimal
- container: ''
  name: expenses
  type: decimal
- container: ''
  name: dt_posted
  type: dateTime
- container: ''
  name: registrant
  type: reference
- container: ''
  name: client
  type: reference
- container: set
  name: lobbying_activities
  type: ''
- container: ''
  name: general_issue_code
  type: string
- container: ''
  name: general_issue_code_display
  type: string
- container: set
  name: government_entities
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: country
  type: string
property_count: 19
provider_name: US Senate
provider_slug: us-senate
slug: us-senate-context
source_filename: us-senate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"lda\": \"https://lda.senate.gov/vocab/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n\n    \"LDAFiling\": \"lda:Filing\",\n    \"Registrant\": \"org:Organization\",\n    \"Client\": \"org:Organization\",\n    \"Lobbyist\": \"schema:Person\",\n\n    \"filing_uuid\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filing_type\": {\n      \"@id\": \"lda:filingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filing_year\": {\n      \"@id\": \"lda:filingYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filing_period\": {\n      \"@id\": \"lda:filingPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"income\": {\n      \"@id\": \"lda:income\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expenses\": {\n      \"@id\": \"\
  lda:expenses\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dt_posted\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"registrant\": {\n      \"@id\": \"lda:registrant\",\n      \"@type\": \"@id\"\n    },\n    \"client\": {\n      \"@id\": \"lda:client\",\n      \"@type\": \"@id\"\n    },\n    \"lobbying_activities\": {\n      \"@id\": \"lda:lobbyingActivities\",\n      \"@container\": \"@set\"\n    },\n    \"general_issue_code\": {\n      \"@id\": \"lda:issueCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"general_issue_code_display\": {\n      \"@id\": \"lda:issueName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"government_entities\": {\n      \"@id\": \"lda:governmentEntities\",\n      \"@container\": \"@set\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"first_name\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_name\"\
  : {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-senate/refs/heads/main/json-ld/us-senate-context.jsonld
tags:
- Federal Government
- Lobbying
- Government Transparency
- Campaign Finance
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
