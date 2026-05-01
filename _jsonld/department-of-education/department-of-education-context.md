---
class_count: 0
classes: []
context_file: json-ld/department-of-education-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/json-ld/department-of-education-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Education from Department of Education.
layout: jsonld
name: Department Of Education Context
namespaces:
- prefix: ed
  uri: https://collegescorecard.ed.gov/data/
properties:
- container: ''
  name: School
  type: ''
- container: ''
  name: Cost
  type: ''
- container: ''
  name: Earnings
  type: ''
- container: ''
  name: Completion
  type: ''
- container: ''
  name: Dataset
  type: ''
property_count: 5
provider_name: Department of Education
provider_slug: department-of-education
slug: department-of-education-context
source_filename: department-of-education-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ed\": \"https://collegescorecard.ed.gov/data/\",\n    \"School\": {\n      \"@id\": \"https://schema.org/CollegeOrUniversity\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"city\": \"https://schema.org/addressLocality\",\n        \"state\": \"https://schema.org/addressRegion\",\n        \"zip\": \"https://schema.org/postalCode\",\n        \"url\": \"https://schema.org/url\"\n      }\n    },\n    \"Cost\": {\n      \"@id\": \"ed:cost\",\n      \"@context\": {\n        \"tuition\": \"https://schema.org/price\",\n        \"attendance\": \"https://schema.org/totalPrice\",\n        \"netPrice\": \"https://schema.org/priceComponent\"\n      }\n    },\n    \"Earnings\": {\n      \"@id\": \"ed:earnings\",\n      \"@context\": {\n        \"median\": \"https://schema.org/value\",\n        \"p25\": \"https://schema.org/lowPrice\"\
  ,\n        \"p75\": \"https://schema.org/highPrice\",\n        \"yearsAfter\": \"https://schema.org/duration\"\n      }\n    },\n    \"Completion\": {\n      \"@id\": \"ed:completion\",\n      \"@context\": {\n        \"rate\": \"https://schema.org/percentage\",\n        \"title\": \"https://schema.org/educationalCredentialAwarded\"\n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"publisher\": \"https://schema.org/publisher\",\n        \"license\": \"https://schema.org/license\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/json-ld/department-of-education-context.jsonld
tags:
- College Scorecard
- Education
- Federal Government
- Higher Education
- IPEDS
- K-12
- NCES
- Open Data
- Postsecondary
- JSON-LD
- Linked Data
- Semantic Web
---
