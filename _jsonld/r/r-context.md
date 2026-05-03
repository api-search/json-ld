---
api_specs:
- filename: r-metacran-crandb-openapi.yml
  format: yaml
  label: METACRAN CranDB API
  slug: metacran-crandb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-crandb-openapi.yml
- filename: r-metacran-cranlogs-openapi.yml
  format: yaml
  label: METACRAN CranLogs API
  slug: metacran-cranlogs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-cranlogs-openapi.yml
- filename: r-rversions-openapi.yml
  format: yaml
  label: R Versions API
  slug: rversions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-rversions-openapi.yml
class_count: 8
classes:
- name
- version
- description
- title
- author
- package
- depends
- suggests
context_file: json-ld/r-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/json-ld/r-context.jsonld
description: JSON-LD context defining the semantic vocabulary for R from R.
layout: jsonld
name: R Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: r
  uri: https://r-project.org/terms/
properties:
- container: ''
  name: Package
  type: reference
- container: ''
  name: maintainer
  type: schema:Person
- container: ''
  name: license
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: downloads
  type: integer
- container: ''
  name: start
  type: date
- container: ''
  name: end
  type: date
- container: ''
  name: day
  type: date
- container: ''
  name: imports
  type: reference
- container: ''
  name: repository
  type: reference
property_count: 10
provider_name: R
provider_slug: r
slug: r-context
source_filename: r-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"r\": \"https://r-project.org/terms/\",\n\n    \"Package\": {\n      \"@id\": \"doap:Project\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"version\": \"doap:revision\",\n    \"description\": \"schema:description\",\n    \"title\": \"dcterms:title\",\n    \"author\": \"dcterms:creator\",\n    \"maintainer\": {\n      \"@id\": \"dcterms:maintainer\",\n      \"@type\": \"schema:Person\"\n    },\n    \"license\": {\n      \"@id\": \"doap:license\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"downloads\": {\n      \"@id\": \"schema:downloadCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"package\": \"schema:name\",\n    \"\
  start\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"day\": {\n      \"@id\": \"schema:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"depends\": \"doap:implements\",\n    \"imports\": {\n      \"@id\": \"schema:softwareRequirements\",\n      \"@type\": \"@id\"\n    },\n    \"suggests\": \"schema:softwareRequirements\",\n    \"repository\": {\n      \"@id\": \"doap:repository\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/json-ld/r-context.jsonld
tags:
- R
- Statistics
- Data Science
- Open Source
- Programming Language
- JSON-LD
- Linked Data
- Semantic Web
---
