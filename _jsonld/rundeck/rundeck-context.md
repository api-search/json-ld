---
api_specs:
- filename: rundeck-openapi.yml
  format: yaml
  label: Rundeck API
  slug: rundeck-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/openapi/rundeck-openapi.yml
class_count: 0
classes: []
context_file: json-ld/rundeck-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/json-ld/rundeck-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rundeck from Rundeck.
layout: jsonld
name: Rundeck Context
namespaces:
- prefix: rundeck
  uri: https://rundeck.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: Execution
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Node
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: SystemInfo
  type: ''
property_count: 6
provider_name: Rundeck
provider_slug: rundeck
slug: rundeck-context
source_filename: rundeck-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rundeck\": \"https://rundeck.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Job\": {\n      \"@id\": \"rundeck:Job\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"group\": \"rundeck:jobGroup\",\n        \"project\": \"rundeck:projectName\",\n        \"description\": \"schema:description\",\n        \"href\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"permalink\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"scheduled\": \"rundeck:isScheduled\",\n        \"scheduleEnabled\": \"rundeck:scheduleEnabled\",\n        \"enabled\": \"rundeck:isEnabled\",\n        \"averageDuration\": \"rundeck:averageDuration\",\n        \"options\": \"rundeck:jobOptions\"\
  ,\n        \"loglevel\": \"rundeck:logLevel\"\n      }\n    },\n\n    \"Execution\": {\n      \"@id\": \"rundeck:Execution\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"rundeck:executionStatus\",\n        \"project\": \"rundeck:projectName\",\n        \"user\": \"schema:agent\",\n        \"dateStarted\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateEnded\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"argstring\": \"rundeck:argumentString\",\n        \"serverUUID\": \"rundeck:serverNode\",\n        \"href\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"rundeck:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"config\": \"rundeck:projectConfig\"\n      }\n    },\n\n    \"Node\": {\n      \"@id\": \"rundeck:Node\",\n      \"@context\": {\n        \"nodename\": \"schema:name\",\n        \"hostname\": \"schema:domainIncludes\",\n        \"username\": \"rundeck:sshUsername\",\n        \"description\": \"schema:description\",\n        \"tags\": \"schema:keywords\",\n        \"osFamily\": \"rundeck:osFamily\",\n        \"osName\": \"rundeck:osName\",\n        \"osArch\": \"rundeck:osArchitecture\",\n        \"osVersion\": \"rundeck:osVersion\"\n      }\n    },\n\n    \"Token\": {\n      \"@id\": \"rundeck:ApiToken\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"user\": \"schema:agent\",\n        \"roles\": \"rundeck:tokenRoles\",\n        \"expiration\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expired\": \"rundeck:isExpired\",\n        \"creator\": \"\
  rundeck:tokenCreator\"\n      }\n    },\n\n    \"SystemInfo\": {\n      \"@id\": \"rundeck:SystemInfo\",\n      \"@context\": {\n        \"version\": \"schema:version\",\n        \"node\": \"schema:name\",\n        \"serverUUID\": \"schema:identifier\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/json-ld/rundeck-context.jsonld
tags:
- Automation
- DevOps
- Job Scheduling
- Orchestration
- Workflow
- Runbook
- Open Source
- IT Operations
- JSON-LD
- Linked Data
- Semantic Web
---
