---
api_specs:
- filename: stackone-openapi.yml
  format: yaml
  label: StackOne
  slug: stackone
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stackone/refs/heads/main/openapi/stackone-openapi.yml
class_count: 11
classes:
- remote_id
- account_id
- first_name
- last_name
- email
- phone
- job_title
- department
- start_date
- created_at
- updated_at
context_file: json-ld/stackone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stackone/refs/heads/main/json-ld/stackone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stackone from StackOne.
layout: jsonld
name: Stackone Context
namespaces:
- prefix: stackone
  uri: https://api.stackone.com/schema/
properties:
- container: ''
  name: Employee
  type: reference
- container: ''
  name: Candidate
  type: reference
- container: ''
  name: Job
  type: reference
- container: ''
  name: Contact
  type: reference
- container: ''
  name: Campaign
  type: reference
property_count: 5
provider_name: StackOne
provider_slug: stackone
slug: stackone-context
source_filename: stackone-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stackone\": \"https://api.stackone.com/schema/\",\n    \"remote_id\": \"stackone:remoteIdentifier\",\n    \"account_id\": \"stackone:accountIdentifier\",\n    \"Employee\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"Candidate\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"Job\": {\n      \"@id\": \"schema:JobPosting\",\n      \"@type\": \"@id\"\n    },\n    \"Contact\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"Campaign\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"job_title\": \"schema:jobTitle\",\n    \"department\": \"schema:department\",\n    \"start_date\": \"schema:startDate\",\n    \"created_at\": \"schema:dateCreated\"\
  ,\n    \"updated_at\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stackone/refs/heads/main/json-ld/stackone-context.jsonld
tags:
- Integrations
- iPaaS
- JSON-LD
- Linked Data
- Semantic Web
---
