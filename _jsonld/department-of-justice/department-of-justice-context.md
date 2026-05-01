---
class_count: 0
classes: []
context_file: json-ld/department-of-justice-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-justice/refs/heads/main/json-ld/department-of-justice-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Justice from Department of Justice.
layout: jsonld
name: Department Of Justice Context
namespaces:
- prefix: doj
  uri: https://www.justice.gov/
properties:
- container: ''
  name: PressRelease
  type: ''
- container: ''
  name: Speech
  type: ''
- container: ''
  name: BlogEntry
  type: ''
- container: ''
  name: FOIAReport
  type: ''
- container: ''
  name: Victimization
  type: ''
- container: ''
  name: Incident
  type: ''
- container: ''
  name: Dataset
  type: ''
property_count: 7
provider_name: Department of Justice
provider_slug: department-of-justice
slug: department-of-justice-context
source_filename: department-of-justice-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"doj\": \"https://www.justice.gov/\",\n    \"PressRelease\": {\n      \"@id\": \"https://schema.org/NewsArticle\",\n      \"@context\": {\n        \"uuid\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/headline\",\n        \"date\": \"https://schema.org/datePublished\",\n        \"body\": \"https://schema.org/articleBody\",\n        \"component\": \"https://schema.org/sourceOrganization\"\n      }\n    },\n    \"Speech\": {\n      \"@id\": \"https://schema.org/Article\",\n      \"@context\": {\n        \"uuid\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/headline\",\n        \"date\": \"https://schema.org/datePublished\",\n        \"speaker\": \"https://schema.org/author\",\n        \"body\": \"https://schema.org/articleBody\"\n      }\n    },\n    \"BlogEntry\": {\n      \"@id\": \"https://schema.org/BlogPosting\",\n      \"@context\": {\n  \
  \      \"uuid\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/headline\",\n        \"date\": \"https://schema.org/datePublished\",\n        \"body\": \"https://schema.org/articleBody\"\n      }\n    },\n    \"FOIAReport\": {\n      \"@id\": \"doj:foia/annual-report\",\n      \"@context\": {\n        \"agency\": \"https://schema.org/sourceOrganization\",\n        \"year\": \"https://schema.org/datePublished\",\n        \"format\": \"https://schema.org/encodingFormat\"\n      }\n    },\n    \"Victimization\": {\n      \"@id\": \"doj:bjs/ncvs\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"category\": \"https://schema.org/category\",\n        \"rate\": \"https://schema.org/value\",\n        \"count\": \"https://schema.org/value\"\n      }\n    },\n    \"Incident\": {\n      \"@id\": \"doj:bjs/nibrs\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"offenseType\": \"https://schema.org/category\"\
  ,\n        \"victimization\": \"https://schema.org/about\",\n        \"estimate\": \"https://schema.org/value\"\n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"publisher\": \"https://schema.org/publisher\",\n        \"license\": \"https://schema.org/license\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-justice/refs/heads/main/json-ld/department-of-justice-context.jsonld
tags:
- Bureau of Justice Statistics
- Crime
- Federal Government
- FOIA
- Justice
- News
- Open Data
- Press Releases
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---
