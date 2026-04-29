---
api_specs:
- filename: oracle-integration-developer-api.yaml
  format: yaml
  label: Oracle Integration Developer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/openapi/oracle-integration-developer-api.yaml
- filename: oracle-integration-process-automation-api.yaml
  format: yaml
  label: Oracle Integration Process Automation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/openapi/oracle-integration-process-automation-api.yaml
class_count: 3
classes:
- ProcessInstance
- Task
- DecisionModel
context_file: json-ld/oracle-integration-process-automation-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/json-ld/oracle-integration-process-automation-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Integration Process Automation Api from Oracle Integration.
layout: jsonld
name: Oracle Integration Process Automation Api Context
namespaces:
- prefix: oracle
  uri: https://docs.oracle.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: processId
  type: string
- container: ''
  name: processName
  type: string
- container: ''
  name: processDefId
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: assignee
  type: string
- container: ''
  name: dueDate
  type: dateTime
- container: ''
  name: processName_task
  type: string
- container: ''
  name: outcome
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: spaceId
  type: string
property_count: 16
provider_name: Oracle Integration
provider_slug: oracle-integration
slug: oracle-integration-process-automation-api-context
source_filename: oracle-integration-process-automation-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oracle\": \"https://docs.oracle.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProcessInstance\": \"oracle:ProcessInstance\",\n    \"Task\": \"oracle:Task\",\n    \"DecisionModel\": \"oracle:DecisionModel\",\n    \"processId\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"processName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"processDefId\": {\"@id\": \"oracle:processDefId\", \"@type\": \"xsd:string\"},\n    \"state\": {\"@id\": \"oracle:state\", \"@type\": \"xsd:string\"},\n    \"priority\": {\"@id\": \"oracle:priority\", \"@type\": \"xsd:integer\"},\n    \"title\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"createdBy\": {\"@id\": \"oracle:createdBy\", \"@type\": \"xsd:string\"},\n    \"createdDate\": {\"@id\": \"schema:dateCreated\", \"@type\"\
  : \"xsd:dateTime\"},\n    \"id\": {\"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\"},\n    \"assignee\": {\"@id\": \"oracle:assignee\", \"@type\": \"xsd:string\"},\n    \"dueDate\": {\"@id\": \"oracle:dueDate\", \"@type\": \"xsd:dateTime\"},\n    \"processName_task\": {\"@id\": \"oracle:processName\", \"@type\": \"xsd:string\"},\n    \"outcome\": {\"@id\": \"oracle:outcome\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"spaceId\": {\"@id\": \"oracle:spaceId\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/json-ld/oracle-integration-process-automation-api-context.jsonld
tags:
- API Management
- Automation
- B2B Integration
- Cloud Integration
- Enterprise Integration
- Integration
- iPaaS
- Process Automation
- JSON-LD
- Linked Data
- Semantic Web
---
