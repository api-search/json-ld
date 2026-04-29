---
api_specs:
- filename: knit-unified-api-openapi.yml
  format: yaml
  label: Knit Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/openapi/knit-unified-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/knit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/json-ld/knit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Knit from Knit.
layout: jsonld
name: Knit Context
namespaces:
- prefix: knit
  uri: https://api.getknit.dev/v1/
properties:
- container: ''
  name: Employee
  type: ''
- container: ''
  name: Department
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: TimeOff
  type: ''
- container: ''
  name: Integration
  type: ''
property_count: 5
provider_name: Knit
provider_slug: knit
slug: knit-context
source_filename: knit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"knit\": \"https://api.getknit.dev/v1/\",\n    \"Employee\": {\n      \"@id\": \"knit:Employee\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"first_name\": \"schema:givenName\",\n        \"last_name\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"job_title\": \"schema:jobTitle\",\n        \"department\": \"schema:department\",\n        \"location\": \"schema:workLocation\",\n        \"employment_status\": \"knit:employmentStatus\",\n        \"start_date\": \"schema:startDate\",\n        \"termination_date\": \"knit:terminationDate\",\n        \"manager_id\": \"knit:managerId\",\n        \"integration_id\": \"knit:integrationId\"\n      }\n    },\n    \"Department\": {\n      \"@id\": \"knit:Department\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"parent_id\": \"knit:parentDepartmentId\"\
  \n      }\n    },\n    \"Location\": {\n      \"@id\": \"knit:Location\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n    \"TimeOff\": {\n      \"@id\": \"knit:TimeOff\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"employee_id\": \"knit:employeeId\",\n        \"type\": \"knit:leaveType\",\n        \"status\": \"knit:leaveStatus\",\n        \"start_date\": \"schema:startDate\",\n        \"end_date\": \"schema:endDate\"\n      }\n    },\n    \"Integration\": {\n      \"@id\": \"knit:Integration\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"provider\": \"schema:name\",\n        \"status\": \"knit:integrationStatus\",\n        \"created_at\": \"schema:dateCreated\",\n    \
  \    \"last_synced_at\": \"knit:lastSyncedAt\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/knit/refs/heads/main/json-ld/knit-context.jsonld
tags:
- B2B
- HR Integrations
- HRIS
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
