---
api_specs:
- filename: smartrecruiters-posting-openapi.yml
  format: yaml
  label: SmartRecruiters Posting API
  slug: posting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-posting-openapi.yml
- filename: smartrecruiters-jobs-openapi.yml
  format: yaml
  label: SmartRecruiters Job API
  slug: job-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-jobs-openapi.yml
- filename: smartrecruiters-candidates-openapi.yml
  format: yaml
  label: SmartRecruiters Candidate API
  slug: candidate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-candidates-openapi.yml
class_count: 37
classes:
- Job
- Candidate
- Application
- id
- title
- status
- department
- location
- country
- city
- region
- remote
- industry
- experienceLevel
- typeOfEmployment
- hiringTeam
- jobOwner
- recruiters
- hiringManagers
- firstName
- lastName
- email
- phoneNumber
- web
- linkedIn
- portfolio
- tags
- consent
- sourceDetails
- createdOn
- updatedOn
- appliedOn
- postingId
- companyIdentifier
- totalFound
- limit
- offset
context_file: json-ld/smartrecruiters-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/json-ld/smartrecruiters-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smartrecruiters from SmartRecruiters.
layout: jsonld
name: Smartrecruiters Context
namespaces:
- prefix: sr
  uri: https://api.smartrecruiters.com/vocab#
properties: []
property_count: 0
provider_name: SmartRecruiters
provider_slug: smartrecruiters
slug: smartrecruiters-context
source_filename: smartrecruiters-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sr\": \"https://api.smartrecruiters.com/vocab#\",\n    \"Job\": \"JobPosting\",\n    \"Candidate\": \"Person\",\n    \"Application\": \"JobApplication\",\n    \"id\": \"@id\",\n    \"title\": \"title\",\n    \"status\": \"sr:status\",\n    \"department\": \"department\",\n    \"location\": \"jobLocation\",\n    \"country\": \"addressCountry\",\n    \"city\": \"addressLocality\",\n    \"region\": \"addressRegion\",\n    \"remote\": \"sr:remote\",\n    \"industry\": \"industry\",\n    \"experienceLevel\": \"experienceRequirements\",\n    \"typeOfEmployment\": \"employmentType\",\n    \"hiringTeam\": \"sr:hiringTeam\",\n    \"jobOwner\": \"sr:jobOwner\",\n    \"recruiters\": \"sr:recruiters\",\n    \"hiringManagers\": \"sr:hiringManagers\",\n    \"firstName\": \"givenName\",\n    \"lastName\": \"familyName\",\n    \"email\": \"email\",\n    \"phoneNumber\": \"telephone\",\n    \"web\": \"sameAs\",\n    \"linkedIn\"\
  : \"sr:linkedIn\",\n    \"portfolio\": \"url\",\n    \"tags\": \"keywords\",\n    \"consent\": \"sr:gdprConsent\",\n    \"sourceDetails\": \"sr:sourceDetails\",\n    \"createdOn\": \"dateCreated\",\n    \"updatedOn\": \"dateModified\",\n    \"appliedOn\": \"datePosted\",\n    \"postingId\": \"identifier\",\n    \"companyIdentifier\": \"sr:companyIdentifier\",\n    \"totalFound\": \"numberOfItems\",\n    \"limit\": \"sr:limit\",\n    \"offset\": \"sr:offset\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/json-ld/smartrecruiters-context.jsonld
tags:
- Human Resources
- Recruiting
- Talent Acquisition
- Applicant Tracking
- HR Technology
- JSON-LD
- Linked Data
- Semantic Web
---
