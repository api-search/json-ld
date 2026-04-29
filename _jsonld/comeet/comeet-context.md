---
api_specs:
- filename: comeet-careers-api-openapi.yml
  format: yaml
  label: Comeet Careers API
  slug: comeet-careers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/openapi/comeet-careers-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/comeet-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/json-ld/comeet-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Comeet from Comeet.
layout: jsonld
name: Comeet Context
namespaces:
- prefix: comeet
  uri: https://comeet.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Position
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Company
  type: ''
property_count: 3
provider_name: Comeet
provider_slug: comeet
slug: comeet-context
source_filename: comeet-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"comeet\": \"https://comeet.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Position\": {\n      \"@id\": \"schema:JobPosting\",\n      \"@context\": {\n        \"uid\": \"@id\",\n        \"name\": \"schema:title\",\n        \"department\": {\n          \"@id\": \"schema:hiringOrganization\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": \"schema:jobLocation\",\n        \"company_department\": {\n          \"@id\": \"comeet:companyDepartment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url_active_after\": {\n          \"@id\": \"schema:datePosted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url_comeet_hosted_page\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"details\": \"schema:description\",\n  \
  \      \"status\": {\n          \"@id\": \"comeet:positionStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"country\": \"schema:addressCountry\",\n        \"city\": \"schema:addressLocality\",\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Company\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"uid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"token\": {\n          \"@id\": \"comeet:companyToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/json-ld/comeet-context.jsonld
tags:
- ATS
- Candidates
- Careers
- Interviews
- Jobs
- Recruiting
- Talent Acquisition
- JSON-LD
- Linked Data
- Semantic Web
---
