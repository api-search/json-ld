---
class_count: 0
classes: []
context_file: json-ld/department-of-labor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-labor/refs/heads/main/json-ld/department-of-labor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Labor from Department of Labor.
layout: jsonld
name: Department Of Labor Context
namespaces:
- prefix: dol
  uri: https://dataportal.dol.gov/
- prefix: bls
  uri: https://www.bls.gov/
properties:
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Series
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: EnforcementCase
  type: ''
- container: ''
  name: OccupationalInjury
  type: ''
property_count: 5
provider_name: Department of Labor
provider_slug: department-of-labor
slug: department-of-labor-context
source_filename: department-of-labor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dol\": \"https://dataportal.dol.gov/\",\n    \"bls\": \"https://www.bls.gov/\",\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"agency\": \"https://schema.org/sourceOrganization\",\n        \"publisher\": \"https://schema.org/publisher\",\n        \"license\": \"https://schema.org/license\"\n      }\n    },\n    \"Series\": {\n      \"@id\": \"bls:developers/api_signature_v2.htm\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"frequency\": \"https://schema.org/temporalCoverage\",\n        \"units\": \"https://schema.org/unitText\",\n        \"seasonal\": \"https://schema.org/keywords\"\n      }\n    },\n \
  \   \"Observation\": {\n      \"@id\": \"bls:observation\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"period\": \"https://schema.org/temporalCoverage\",\n        \"value\": \"https://schema.org/value\",\n        \"series\": \"https://schema.org/about\"\n      }\n    },\n    \"EnforcementCase\": {\n      \"@id\": \"https://data.dol.gov/\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"agency\": \"https://schema.org/sourceOrganization\",\n        \"employer\": \"https://schema.org/employer\",\n        \"violation\": \"https://schema.org/about\",\n        \"penalty\": \"https://schema.org/amount\",\n        \"openDate\": \"https://schema.org/startDate\",\n        \"closeDate\": \"https://schema.org/endDate\"\n      }\n    },\n    \"OccupationalInjury\": {\n      \"@id\": \"https://www.osha.gov\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"industry\": \"\
  https://schema.org/category\",\n        \"incidentRate\": \"https://schema.org/value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-labor/refs/heads/main/json-ld/department-of-labor-context.jsonld
tags:
- BLS
- Employment
- Enforcement
- Federal Government
- Labor
- Open Data
- Statistics
- Wages
- Workforce
- JSON-LD
- Linked Data
- Semantic Web
---
