---
api_specs:
- filename: uspto-patent-api-openapi.yml
  format: yaml
  label: USPTO Patent & Trademark API
  slug: patent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/openapi/uspto-patent-api-openapi.yml
- filename: index.html
  format: yaml
  label: USPTO Patent Trial and Appeal Board (PTAB) API
  slug: ptab-api
  spec_type: OpenAPI
  url: https://data.uspto.gov/swagger/index.html
- filename: tsdr-api-v1
  format: yaml
  label: USPTO Trademark Status and Document Retrieval (TSDR) API
  slug: tsdr-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/swagger/tsdr-api-v1
- filename: oa_actions.json
  format: json
  label: USPTO Office Action Text Retrieval API
  slug: office-actions-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/ds-api/swagger/docs/oa_actions.json
- filename: enriched_cited_reference_metadata.json
  format: json
  label: USPTO Enriched Citation API
  slug: enriched-citation-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json
class_count: 24
classes:
- Patent
- Trademark
- Inventor
- Assignee
- PTABTrial
- applicationNumber
- patentNumber
- title
- abstract
- status
- patentType
- cpcClassifications
- claims
- firstName
- lastName
- city
- state
- country
- serialNumber
- markLiteralElements
- goodsAndServices
- trialNumber
- proceedingType
- petitionerName
context_file: json-ld/uspto-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/json-ld/uspto-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uspto from USPTO.
layout: jsonld
name: Uspto Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: patent
  uri: https://data.uspto.gov/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: filingDate
  type: date
- container: ''
  name: grantDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: inventors
  type: schema:Person
- container: ''
  name: assignees
  type: schema:Organization
- container: ''
  name: registrationDate
  type: date
- container: ''
  name: patentOwnerName
  type: reference
property_count: 7
provider_name: USPTO
provider_slug: uspto
slug: uspto-context
source_filename: uspto-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"patent\": \"https://data.uspto.gov/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Patent\": \"schema:CreativeWork\",\n    \"Trademark\": \"schema:Brand\",\n    \"Inventor\": \"schema:Person\",\n    \"Assignee\": \"schema:Organization\",\n    \"PTABTrial\": \"schema:LegalCase\",\n\n    \"applicationNumber\": \"schema:identifier\",\n    \"patentNumber\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"abstract\": \"schema:abstract\",\n    \"filingDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"grantDate\": {\n      \"@id\": \"patent:grantDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": \"schema:actionStatus\",\n    \"patentType\": \"schema:additionalType\",\n    \"inventors\": {\n\
  \      \"@id\": \"schema:author\",\n      \"@type\": \"schema:Person\"\n    },\n    \"assignees\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"cpcClassifications\": \"patent:classification\",\n    \"claims\": \"patent:claims\",\n\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n\n    \"serialNumber\": \"schema:identifier\",\n    \"markLiteralElements\": \"schema:name\",\n    \"registrationDate\": {\n      \"@id\": \"patent:registrationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"goodsAndServices\": \"schema:description\",\n\n    \"trialNumber\": \"schema:identifier\",\n    \"proceedingType\": \"schema:additionalType\",\n    \"petitionerName\": \"schema:participant\",\n    \"patentOwnerName\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/json-ld/uspto-context.jsonld
tags:
- Government
- Intellectual Property
- Open Data
- Patents
- Regulatory
- Trademarks
- USPTO
- JSON-LD
- Linked Data
- Semantic Web
---
