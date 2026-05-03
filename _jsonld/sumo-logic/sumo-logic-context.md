---
api_specs:
- filename: sumo-logic-openapi.yml
  format: yaml
  label: Sumo Logic API
  slug: sumo-logic
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sumo-logic/refs/heads/main/openapi/sumo-logic-openapi.yml
class_count: 18
classes:
- id
- name
- description
- email
- firstName
- lastName
- isActive
- isLocked
- isMfaEnabled
- roleIds
- monitorType
- status
- queries
- triggers
- createdAt
- modifiedAt
- createdBy
- lastLoginTimestamp
context_file: json-ld/sumo-logic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sumo-logic/refs/heads/main/json-ld/sumo-logic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sumo Logic from Sumo Logic.
layout: jsonld
name: Sumo Logic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sumo
  uri: https://api.sumologic.com/vocab#
properties:
- container: ''
  name: User
  type: reference
- container: ''
  name: Role
  type: reference
- container: ''
  name: Dashboard
  type: reference
- container: ''
  name: Monitor
  type: reference
- container: ''
  name: SearchJob
  type: reference
- container: ''
  name: AccessKey
  type: reference
- container: ''
  name: IngestBudget
  type: reference
- container: ''
  name: Connection
  type: reference
property_count: 8
provider_name: Sumo Logic
provider_slug: sumo-logic
slug: sumo-logic-context
source_filename: sumo-logic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sumo\": \"https://api.sumologic.com/vocab#\",\n\n    \"User\": {\n      \"@id\": \"sumo:User\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Person\"\n    },\n    \"Role\": {\n      \"@id\": \"sumo:Role\",\n      \"@type\": \"@id\"\n    },\n    \"Dashboard\": {\n      \"@id\": \"sumo:Dashboard\",\n      \"@type\": \"@id\"\n    },\n    \"Monitor\": {\n      \"@id\": \"sumo:Monitor\",\n      \"@type\": \"@id\"\n    },\n    \"SearchJob\": {\n      \"@id\": \"sumo:SearchJob\",\n      \"@type\": \"@id\"\n    },\n    \"AccessKey\": {\n      \"@id\": \"sumo:AccessKey\",\n      \"@type\": \"@id\"\n    },\n    \"IngestBudget\": {\n      \"@id\": \"sumo:IngestBudget\",\n      \"@type\": \"@id\"\n    },\n    \"Connection\": {\n      \"@id\": \"sumo:Connection\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"\
  schema:description\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"isActive\": \"sumo:isActive\",\n    \"isLocked\": \"sumo:isLocked\",\n    \"isMfaEnabled\": \"sumo:isMfaEnabled\",\n    \"roleIds\": \"sumo:roleIds\",\n    \"monitorType\": \"sumo:monitorType\",\n    \"status\": \"schema:status\",\n    \"queries\": \"sumo:queries\",\n    \"triggers\": \"sumo:triggers\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"modifiedAt\": \"schema:dateModified\",\n    \"createdBy\": \"schema:author\",\n    \"lastLoginTimestamp\": \"sumo:lastLoginTimestamp\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sumo-logic/refs/heads/main/json-ld/sumo-logic-context.jsonld
tags:
- Logging
- Observability
- Security
- Monitoring
- Analytics
- DevOps
- SIEM
- JSON-LD
- Linked Data
- Semantic Web
---
