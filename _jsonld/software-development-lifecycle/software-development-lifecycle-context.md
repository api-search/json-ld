---
api_specs:
- filename: api.github.com.json
  format: json
  label: Code and Review APIs
  slug: code-and-review
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
class_count: 30
classes:
- Sprint
- Deployment
- BuildArtifact
- SecurityScan
- TestRun
- Release
- Incident
- id
- type
- name
- description
- version
- goal
- capacity
- velocity
- workItems
- team
- board
- completedPoints
- application
- environment
- strategy
- status
- triggeredBy
- pipeline
- commit
- rollbackOf
- severity
- affectedServices
- language
context_file: json-ld/software-development-lifecycle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-development-lifecycle/refs/heads/main/json-ld/software-development-lifecycle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Development Lifecycle from Software Development Lifecycle.
layout: jsonld
name: Software Development Lifecycle Context
namespaces:
- prefix: sdlc
  uri: https://api-evangelist.com/vocab/sdlc#
- prefix: schema
  uri: https://schema.org/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: healthCheckUrl
  type: reference
- container: ''
  name: resolvedAt
  type: dateTime
- container: ''
  name: repository
  type: reference
- container: ''
  name: homepage
  type: reference
- container: ''
  name: license
  type: reference
property_count: 11
provider_name: Software Development Lifecycle
provider_slug: software-development-lifecycle
slug: software-development-lifecycle-context
source_filename: software-development-lifecycle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sdlc\": \"https://api-evangelist.com/vocab/sdlc#\",\n    \"schema\": \"https://schema.org/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Sprint\": \"sdlc:Sprint\",\n    \"Deployment\": \"sdlc:Deployment\",\n    \"BuildArtifact\": \"sdlc:BuildArtifact\",\n    \"SecurityScan\": \"sdlc:SecurityScan\",\n    \"TestRun\": \"sdlc:TestRun\",\n    \"Release\": \"sdlc:Release\",\n    \"Incident\": \"sdlc:Incident\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"goal\": \"sdlc:goal\",\n    \"capacity\": \"sdlc:capacity\",\n    \"velocity\"\
  : \"sdlc:velocity\",\n    \"workItems\": \"sdlc:workItems\",\n    \"team\": \"sdlc:team\",\n    \"board\": \"sdlc:board\",\n    \"completedPoints\": \"sdlc:completedPoints\",\n    \"startDate\": {\n      \"@id\": \"sdlc:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"sdlc:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"application\": \"sdlc:application\",\n    \"environment\": \"sdlc:environment\",\n    \"strategy\": \"sdlc:strategy\",\n    \"status\": \"sdlc:status\",\n    \"triggeredBy\": \"sdlc:triggeredBy\",\n    \"pipeline\": \"sdlc:pipeline\",\n    \"commit\": \"sdlc:commit\",\n    \"startedAt\": {\n      \"@id\": \"sdlc:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"sdlc:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rollbackOf\": \"sdlc:rollbackOf\",\n    \"healthCheckUrl\": {\n      \"@id\": \"sdlc:healthCheckUrl\",\n      \"@type\": \"@id\"\n    },\n\n   \
  \ \"severity\": \"sdlc:severity\",\n    \"affectedServices\": \"sdlc:affectedServices\",\n    \"resolvedAt\": {\n      \"@id\": \"sdlc:resolvedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"repository\": {\n      \"@id\": \"doap:repository\",\n      \"@type\": \"@id\"\n    },\n    \"homepage\": {\n      \"@id\": \"doap:homepage\",\n      \"@type\": \"@id\"\n    },\n    \"language\": \"doap:programming-language\",\n    \"license\": {\n      \"@id\": \"doap:license\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-development-lifecycle/refs/heads/main/json-ld/software-development-lifecycle-context.jsonld
tags:
- Development Process
- Project Management
- Quality Assurance
- Software Engineering
- DevOps
- Platform Engineering
- JSON-LD
- Linked Data
- Semantic Web
---
