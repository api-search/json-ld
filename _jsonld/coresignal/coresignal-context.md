---
api_specs:
- filename: coresignal-multi-source-company-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Company API
  slug: multi-source-company-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-company-api-openapi.yml
- filename: coresignal-multi-source-employee-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Employee API
  slug: multi-source-employee-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-employee-api-openapi.yml
- filename: coresignal-multi-source-jobs-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Jobs API
  slug: multi-source-jobs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-jobs-api-openapi.yml
class_count: 42
classes:
- Company
- Employee
- Job
- id
- name
- full_name
- first_name
- last_name
- title
- description
- headline
- summary
- country
- region
- location
- locality
- headquarters
- industry
- size
- employees_count
- founded
- specialities
- technologies
- domain
- website
- linkedin_url
- twitter_url
- facebook_url
- crunchbase_url
- experience
- education
- skills
- certifications
- company_name
- url
- seniority_level
- employment_type
- date_posted
- salary_currency
- salary_min
- salary_max
- last_updated
context_file: json-ld/coresignal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/json-ld/coresignal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Coresignal from Coresignal.
layout: jsonld
name: Coresignal Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: coresignal
  uri: https://api.coresignal.com/vocab#
properties: []
property_count: 0
provider_name: Coresignal
provider_slug: coresignal
slug: coresignal-context
source_filename: coresignal-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.coresignal.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"coresignal\": \"https://api.coresignal.com/vocab#\",\n    \"Company\": \"schema:Organization\",\n    \"Employee\": \"schema:Person\",\n    \"Job\": \"schema:JobPosting\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"full_name\": \"schema:name\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"title\": \"schema:jobTitle\",\n    \"description\": \"schema:description\",\n    \"headline\": \"schema:description\",\n    \"summary\": \"schema:description\",\n    \"country\": \"schema:addressCountry\",\n    \"region\": \"schema:addressRegion\",\n    \"location\": \"schema:address\",\n    \"locality\": \"schema:addressLocality\",\n    \"headquarters\": \"schema:address\",\n    \"industry\": \"coresignal:industry\",\n    \"size\": \"coresignal:companySize\",\n    \"employees_count\": \"\
  schema:numberOfEmployees\",\n    \"founded\": \"schema:foundingDate\",\n    \"specialities\": \"schema:knowsAbout\",\n    \"technologies\": \"coresignal:technologies\",\n    \"domain\": \"coresignal:domain\",\n    \"website\": \"schema:url\",\n    \"linkedin_url\": \"schema:sameAs\",\n    \"twitter_url\": \"schema:sameAs\",\n    \"facebook_url\": \"schema:sameAs\",\n    \"crunchbase_url\": \"schema:sameAs\",\n    \"experience\": \"schema:hasOccupation\",\n    \"education\": \"schema:alumniOf\",\n    \"skills\": \"schema:knowsAbout\",\n    \"certifications\": \"coresignal:certifications\",\n    \"company_name\": \"schema:hiringOrganization\",\n    \"url\": \"schema:url\",\n    \"seniority_level\": \"coresignal:seniorityLevel\",\n    \"employment_type\": \"schema:employmentType\",\n    \"date_posted\": \"schema:datePosted\",\n    \"salary_currency\": \"schema:salaryCurrency\",\n    \"salary_min\": \"coresignal:salaryMin\",\n    \"salary_max\": \"coresignal:salaryMax\",\n    \"last_updated\"\
  : \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/json-ld/coresignal-context.jsonld
tags:
- Agentic Search
- B2B Data
- Companies
- Company Data
- Data as a Service
- Elasticsearch
- Employee Data
- Employees
- Enrichment
- Firmographics
- Job Postings
- Jobs
- Lead Generation
- People Data
- Sales Intelligence
- Talent Intelligence
- Web Data
- JSON-LD
- Linked Data
- Semantic Web
---
