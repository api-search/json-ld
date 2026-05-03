---
class_count: 4
classes:
- CivilRightsComplaint
- CivilRightsReport
- NoFearActStatistic
- url
context_file: json-ld/us-commission-on-civil-rights-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-commission-on-civil-rights/refs/heads/main/json-ld/us-commission-on-civil-rights-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Commission On Civil Rights from US Commission on Civil Rights.
layout: jsonld
name: Us Commission On Civil Rights Context
namespaces:
- prefix: usccr
  uri: https://www.usccr.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: advisory_committee
  type: string
- container: ''
  name: basis
  type: string
- container: ''
  name: complainant_type
  type: string
- container: ''
  name: complaint_id
  type: string
- container: ''
  name: complaints_filed
  type: integer
- container: ''
  name: complaints_pending
  type: integer
- container: ''
  name: complaints_resolved
  type: integer
- container: ''
  name: federal_agency
  type: string
- container: ''
  name: filing_date
  type: date
- container: ''
  name: findings_of_discrimination
  type: integer
- container: ''
  name: fiscal_year
  type: integer
- container: ''
  name: monetary_benefits
  type: decimal
- container: ''
  name: pdf_url
  type: reference
- container: ''
  name: publication_date
  type: date
- container: ''
  name: quarter
  type: integer
- container: ''
  name: recommendations_count
  type: integer
- container: ''
  name: report_id
  type: string
- container: ''
  name: report_type
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: states_covered
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: title
  type: string
- container: set
  name: topics
  type: string
property_count: 26
provider_name: US Commission on Civil Rights
provider_slug: us-commission-on-civil-rights
slug: us-commission-on-civil-rights-context
source_filename: us-commission-on-civil-rights-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usccr\": \"https://www.usccr.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CivilRightsComplaint\": \"usccr:CivilRightsComplaint\",\n    \"CivilRightsReport\": \"usccr:CivilRightsReport\",\n    \"NoFearActStatistic\": \"usccr:NoFearActStatistic\",\n    \"advisory_committee\": {\n      \"@id\": \"usccr:advisory_committee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basis\": {\n      \"@id\": \"usccr:basis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complainant_type\": {\n      \"@id\": \"usccr:complainant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complaint_id\": {\n      \"@id\": \"usccr:complaint_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complaints_filed\": {\n      \"@id\": \"usccr:complaints_filed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"complaints_pending\"\
  : {\n      \"@id\": \"usccr:complaints_pending\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"complaints_resolved\": {\n      \"@id\": \"usccr:complaints_resolved\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"federal_agency\": {\n      \"@id\": \"usccr:federal_agency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filing_date\": {\n      \"@id\": \"usccr:filing_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"findings_of_discrimination\": {\n      \"@id\": \"usccr:findings_of_discrimination\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fiscal_year\": {\n      \"@id\": \"usccr:fiscal_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"monetary_benefits\": {\n      \"@id\": \"usccr:monetary_benefits\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pdf_url\": {\n      \"@id\": \"usccr:pdf_url\",\n      \"@type\": \"@id\"\n    },\n    \"publication_date\": {\n      \"@id\": \"usccr:publication_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"quarter\"\
  : {\n      \"@id\": \"usccr:quarter\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recommendations_count\": {\n      \"@id\": \"usccr:recommendations_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"report_id\": {\n      \"@id\": \"usccr:report_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"report_type\": {\n      \"@id\": \"usccr:report_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"usccr:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"usccr:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"states_covered\": {\n      \"@id\": \"usccr:states_covered\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"usccr:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"usccr:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"usccr:summary\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"usccr:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topics\": {\n      \"@id\": \"usccr:topics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-commission-on-civil-rights/refs/heads/main/json-ld/us-commission-on-civil-rights-context.jsonld
tags:
- Civil Rights
- Federal Government
- Equal Protection
- Discrimination
- JSON-LD
- Linked Data
- Semantic Web
---
