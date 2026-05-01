---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Talent Solution API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-talent-solution/refs/heads/main/openapi/openapi.yml
class_count: 3
classes:
- Job
- Company
- Tenant
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-talent-solution/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Talent Solution.
layout: jsonld
name: context Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/solutions/talent-solution/docs/reference/rest/v4/
- prefix: name
  uri: https://schema.org/name
- prefix: title
  uri: https://schema.org/jobTitle
- prefix: description
  uri: https://schema.org/description
- prefix: addresses
  uri: https://schema.org/jobLocation
- prefix: employmentTypes
  uri: https://schema.org/employmentType
- prefix: compensationInfo
  uri: https://schema.org/baseSalary
- prefix: postingExpireTime
  uri: https://schema.org/validThrough
- prefix: postingCreateTime
  uri: https://schema.org/datePosted
- prefix: qualifications
  uri: https://schema.org/qualifications
- prefix: responsibilities
  uri: https://schema.org/responsibilities
- prefix: websiteUri
  uri: https://schema.org/url
- prefix: displayName
  uri: https://schema.org/legalName
properties:
- container: ''
  name: company
  type: reference
property_count: 1
provider_name: Google Cloud Talent Solution
provider_slug: google-cloud-talent-solution
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/solutions/talent-solution/docs/reference/rest/v4/\",\n    \"Job\": \"gcloud:projects.tenants.jobs\",\n    \"Company\": \"gcloud:projects.tenants.companies\",\n    \"Tenant\": \"gcloud:projects.tenants\",\n    \"name\": \"https://schema.org/name\",\n    \"title\": \"https://schema.org/jobTitle\",\n    \"description\": \"https://schema.org/description\",\n    \"company\": {\n      \"@id\": \"https://schema.org/hiringOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"addresses\": \"https://schema.org/jobLocation\",\n    \"employmentTypes\": \"https://schema.org/employmentType\",\n    \"compensationInfo\": \"https://schema.org/baseSalary\",\n    \"postingExpireTime\": \"https://schema.org/validThrough\",\n    \"postingCreateTime\": \"https://schema.org/datePosted\",\n    \"qualifications\": \"https://schema.org/qualifications\",\n    \"responsibilities\": \"https://schema.org/responsibilities\"\
  ,\n    \"websiteUri\": \"https://schema.org/url\",\n    \"displayName\": \"https://schema.org/legalName\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-talent-solution/refs/heads/main/json-ld/context.jsonld
tags:
- Google Cloud
- Jobs
- Machine Learning
- Recruitment
- Search
- Talent
- JSON-LD
- Linked Data
- Semantic Web
---
