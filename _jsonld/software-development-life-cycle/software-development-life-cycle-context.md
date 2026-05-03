---
api_specs:
- filename: api.github.com.json
  format: json
  label: Source Control APIs
  slug: source-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
class_count: 34
classes:
- WorkItem
- Pipeline
- Sprint
- Release
- TestSuite
- id
- type
- name
- description
- status
- priority
- storyPoints
- assignee
- reporter
- sprint
- epic
- labels
- acceptanceCriteria
- stages
- steps
- triggers
- branch
- command
- environment
- velocity
- capacity
- version
- releaseNotes
- artifacts
- deployedEnvironments
- testResults
- coverage
- passRate
- failedTests
context_file: json-ld/software-development-life-cycle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-development-life-cycle/refs/heads/main/json-ld/software-development-life-cycle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Development Life Cycle from Software Development Life Cycle.
layout: jsonld
name: Software Development Life Cycle Context
namespaces:
- prefix: sdlc
  uri: https://api-evangelist.com/vocab/sdlc#
- prefix: schema
  uri: https://schema.org/
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
  name: dueDate
  type: date
- container: ''
  name: repository
  type: reference
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
property_count: 6
provider_name: Software Development Life Cycle
provider_slug: software-development-life-cycle
slug: software-development-life-cycle-context
source_filename: software-development-life-cycle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sdlc\": \"https://api-evangelist.com/vocab/sdlc#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"WorkItem\": \"sdlc:WorkItem\",\n    \"Pipeline\": \"sdlc:Pipeline\",\n    \"Sprint\": \"sdlc:Sprint\",\n    \"Release\": \"sdlc:Release\",\n    \"TestSuite\": \"sdlc:TestSuite\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"status\": \"sdlc:status\",\n    \"priority\": \"sdlc:priority\",\n    \"storyPoints\": \"sdlc:storyPoints\",\n    \"assignee\": \"sdlc:assignee\",\n    \"reporter\": \"sdlc:reporter\",\n    \"sprint\": \"sdlc:sprint\",\n    \"epic\": \"sdlc:epic\",\n   \
  \ \"labels\": \"sdlc:labels\",\n    \"acceptanceCriteria\": \"sdlc:acceptanceCriteria\",\n    \"dueDate\": {\n      \"@id\": \"sdlc:dueDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"stages\": \"sdlc:stages\",\n    \"steps\": \"sdlc:steps\",\n    \"triggers\": \"sdlc:triggers\",\n    \"repository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"branch\": \"sdlc:branch\",\n    \"command\": \"sdlc:command\",\n    \"environment\": \"sdlc:environment\",\n\n    \"velocity\": \"sdlc:velocity\",\n    \"capacity\": \"sdlc:capacity\",\n    \"startDate\": {\n      \"@id\": \"sdlc:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"sdlc:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"version\": \"schema:version\",\n    \"releaseNotes\": \"sdlc:releaseNotes\",\n    \"artifacts\": \"sdlc:artifacts\",\n    \"deployedEnvironments\": \"sdlc:deployedEnvironments\",\n\n    \"testResults\": \"sdlc:testResults\"\
  ,\n    \"coverage\": \"sdlc:coverage\",\n    \"passRate\": \"sdlc:passRate\",\n    \"failedTests\": \"sdlc:failedTests\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-development-life-cycle/refs/heads/main/json-ld/software-development-life-cycle-context.jsonld
tags:
- Development Process
- Project Management
- SDLC
- Software Engineering
- DevOps
- CI/CD
- JSON-LD
- Linked Data
- Semantic Web
---
