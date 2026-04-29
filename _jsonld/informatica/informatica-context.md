---
api_specs:
- filename: informatica-platform-rest-api-openapi.yml
  format: yaml
  label: Informatica Platform REST API
  slug: informatica
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/openapi/informatica-platform-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/informatica-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/json-ld/informatica-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Informatica from Informatica.
layout: jsonld
name: Informatica Context
namespaces:
- prefix: infa
  uri: https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/ns#
- prefix: iics
  uri: https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/iics#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
properties:
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Mapping
  type: ''
- container: ''
  name: MappingTask
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: ActivityLogEntry
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Session
  type: ''
property_count: 7
provider_name: Informatica
provider_slug: informatica
slug: informatica-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"infa\": \"https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/ns#\",\n    \"iics\": \"https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/iics#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n\n    \"Connection\": {\n      \"@id\": \"infa:Connection\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orgId\": {\n          \"@id\": \"infa:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\"\
  : \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"infa:connectionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"host\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"infa:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"database\": {\n          \"@id\": \"infa:database\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schema\": {\n          \"@id\": \"infa:databaseSchema\",\n          \"@type\": \"xsd:string\"\n        },\n        \"username\": {\n          \"@id\": \"infa:username\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authenticationType\": {\n          \"@id\": \"infa:authenticationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"codepage\"\
  : {\n          \"@id\": \"infa:codepage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runtimeEnvironmentId\": {\n          \"@id\": \"infa:runtimeEnvironmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"agentId\": {\n          \"@id\": \"infa:secureAgentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedBy\": {\n          \"@id\": \"infa:updatedBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"connParams\": {\n          \"@id\": \"infa:connectionParameters\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Mapping\": {\n      \"@id\": \"infa:Mapping\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orgId\": {\n          \"@id\": \"infa:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedBy\": {\n          \"@id\": \"infa:updatedBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"templateId\": {\n          \"@id\": \"\
  infa:templateId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"deployTime\": {\n          \"@id\": \"infa:deployTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hasParameters\": {\n          \"@id\": \"infa:hasParameters\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"valid\": {\n          \"@id\": \"infa:isValid\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"fixedConnection\": {\n          \"@id\": \"infa:fixedConnection\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tasks\": {\n          \"@id\": \"infa:taskCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"parameters\": {\n          \"@id\": \"infa:parameters\",\n          \"@container\": \"@list\"\n        },\n        \"inOutParameters\": {\n          \"@id\": \"infa:inOutParameters\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"MappingTask\": {\n      \"@id\": \"infa:MappingTask\",\n      \"@context\"\
  : {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orgId\": {\n          \"@id\": \"infa:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mappingId\": {\n          \"@id\": \"infa:mappingId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runtimeEnvironmentId\": {\n          \"@id\": \"infa:runtimeEnvironmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scheduleId\": {\n          \"@id\": \"infa:scheduleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceConnectionId\": {\n          \"@id\": \"infa:sourceConnectionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"targetConnectionId\": {\n  \
  \        \"@id\": \"infa:targetConnectionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"active\": {\n          \"@id\": \"infa:isActive\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"infa:Job\",\n      \"@context\": {\n        \"taskId\": {\n          \"@id\": \"infa:taskId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taskName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taskType\": {\n          \"@id\": \"infa:taskType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runId\": {\n          \"@id\": \"infa:runId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"callbackUrl\"\
  : {\n          \"@id\": \"infa:callbackUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ActivityLogEntry\": {\n      \"@id\": \"infa:ActivityLogEntry\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectId\": {\n          \"@id\": \"infa:objectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runId\": {\n          \"@id\": \"infa:runId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"state\": {\n          \"@id\": \"infa:executionState\",\n          \"@type\": \"xsd:integer\"\n        },\n \
  \       \"successSourceRows\": {\n          \"@id\": \"infa:successSourceRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"failedSourceRows\": {\n          \"@id\": \"infa:failedSourceRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"successTargetRows\": {\n          \"@id\": \"infa:successTargetRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"failedTargetRows\": {\n          \"@id\": \"infa:failedTargetRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"errorMsg\": {\n          \"@id\": \"infa:errorMessage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startedBy\": {\n          \"@id\": \"infa:startedBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runContextType\": {\n          \"@id\": \"infa:runContextType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"infa:Schedule\",\n      \"@context\": {\n        \"id\": {\n  \
  \        \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"interval\": {\n          \"@id\": \"schema:repeatFrequency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"frequency\": {\n          \"@id\": \"infa:frequency\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timezone\": {\n          \"@id\": \"infa:timezone\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"infa:Session\",\n      \"@context\": {\n\
  \        \"icSessionId\": {\n          \"@id\": \"infa:sessionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serverUrl\": {\n          \"@id\": \"infa:serverUrl\",\n          \"@type\": \"@id\"\n        },\n        \"orgId\": {\n          \"@id\": \"infa:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/json-ld/informatica-context.jsonld
tags:
- Address Verification
- B2B Gateway
- Cloud Services
- Data Governance
- Data Integration
- Data Profiling
- Data Quality
- Enterprise Software
- ETL
- IDMC
- IICS
- Master Data Management
- Reference Data Management
- JSON-LD
- Linked Data
- Semantic Web
---
