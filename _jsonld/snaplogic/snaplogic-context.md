---
api_specs:
- filename: snaplogic-public-apis-openapi.yml
  format: yaml
  label: SnapLogic Public APIs
  slug: snaplogic-public-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snaplogic/refs/heads/main/openapi/snaplogic-public-apis-openapi.yml
class_count: 6
classes:
- name
- description
- url
- identifier
- SoftwareApplication
- Organization
context_file: json-ld/snaplogic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snaplogic/refs/heads/main/json-ld/snaplogic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snaplogic from SnapLogic.
layout: jsonld
name: Snaplogic Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: snap
  uri: https://api-evangelist.github.io/snaplogic/vocabulary/
properties:
- container: ''
  name: IntegrationPlatform
  type: schema:SoftwareApplication
- container: ''
  name: Pipeline
  type: schema:Action
- container: ''
  name: Snap
  type: schema:SoftwareApplication
- container: ''
  name: Task
  type: schema:Action
- container: ''
  name: Snaplex
  type: schema:ComputerSystem
- container: ''
  name: RuntimeExecution
  type: schema:Action
- container: ''
  name: ruuid
  type: string
- container: ''
  name: pipelinePath
  type: string
- container: ''
  name: executionStatus
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: elapsedSeconds
  type: decimal
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: triggeringUser
  type: string
- container: ''
  name: snapType
  type: string
- container: ''
  name: recordsIn
  type: integer
- container: ''
  name: recordsOut
  type: integer
- container: ''
  name: bytesProcessed
  type: integer
- container: ''
  name: orgName
  type: string
- container: ''
  name: projectPath
  type: string
- container: ''
  name: snaplexNode
  type: string
- container: ''
  name: taskType
  type: string
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: concurrentExecutions
  type: integer
- container: ''
  name: maxConcurrentExecutions
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 27
provider_name: SnapLogic
provider_slug: snaplogic
slug: snaplogic-context
source_filename: snaplogic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"snap\": \"https://api-evangelist.github.io/snaplogic/vocabulary/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\",\n    \"IntegrationPlatform\": {\n      \"@id\": \"snap:IntegrationPlatform\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Pipeline\": {\n      \"@id\": \"snap:Pipeline\",\n      \"@type\": \"schema:Action\"\n    },\n    \"Snap\": {\n      \"@id\": \"snap:Snap\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Task\": {\n      \"@id\": \"snap:Task\",\n      \"@type\": \"schema:Action\"\n    },\n    \"Snaplex\": {\n      \"@id\": \"snap:Snaplex\",\n      \"@type\": \"schema:ComputerSystem\"\
  \n    },\n    \"RuntimeExecution\": {\n      \"@id\": \"snap:RuntimeExecution\",\n      \"@type\": \"schema:Action\"\n    },\n    \"ruuid\": {\n      \"@id\": \"snap:ruuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelinePath\": {\n      \"@id\": \"snap:pipelinePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionStatus\": {\n      \"@id\": \"snap:executionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"elapsedSeconds\": {\n      \"@id\": \"snap:elapsedSeconds\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"snap:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggeringUser\": {\n      \"@id\": \"snap:triggeringUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapType\": {\n      \"@id\": \"snap:snapType\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"recordsIn\": {\n      \"@id\": \"snap:recordsIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recordsOut\": {\n      \"@id\": \"snap:recordsOut\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bytesProcessed\": {\n      \"@id\": \"snap:bytesProcessed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"orgName\": {\n      \"@id\": \"snap:orgName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectPath\": {\n      \"@id\": \"snap:projectPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snaplexNode\": {\n      \"@id\": \"snap:snaplexNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskType\": {\n      \"@id\": \"snap:taskType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"snap:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"concurrentExecutions\": {\n      \"@id\": \"snap:concurrentExecutions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxConcurrentExecutions\"\
  : {\n      \"@id\": \"snap:maxConcurrentExecutions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snaplogic/refs/heads/main/json-ld/snaplogic-context.jsonld
tags:
- AI
- API Management
- Automation
- Data Integration
- Integrations
- iPaaS
- Management
- JSON-LD
- Linked Data
- Semantic Web
---
