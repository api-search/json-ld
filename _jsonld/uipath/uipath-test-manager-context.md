---
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
class_count: 16
classes:
- CreateProjectRequest
- CreateRequirementRequest
- CreateTestCaseRequest
- CreateTestSetRequest
- ProjectListResponse
- Project
- RequirementListResponse
- Requirement
- TestCaseListResponse
- TestCase
- TestExecutionListResponse
- TestExecution
- TestSetListResponse
- TestSet
- name
- description
context_file: json-ld/uipath-test-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-test-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Test Manager from UiPath.
layout: jsonld
name: Uipath Test Manager Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: externalId
  type: string
- container: set
  name: labels
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: set
  name: projects
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: testCaseCount
  type: integer
- container: ''
  name: requirementCount
  type: integer
- container: set
  name: requirements
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: linkedTestCaseCount
  type: integer
- container: set
  name: testCases
  type: string
- container: ''
  name: automationStatus
  type: string
- container: set
  name: executions
  type: string
- container: ''
  name: testSetId
  type: string
- container: ''
  name: testSetName
  type: string
- container: ''
  name: startedOn
  type: dateTime
- container: ''
  name: finishedOn
  type: dateTime
- container: ''
  name: totalTestCases
  type: integer
- container: ''
  name: passedTestCases
  type: integer
- container: ''
  name: failedTestCases
  type: integer
- container: ''
  name: blockedTestCases
  type: integer
- container: set
  name: testSets
  type: string
property_count: 26
provider_name: UiPath
provider_slug: uipath
slug: uipath-test-manager-context
source_filename: uipath-test-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateProjectRequest\": \"uipath:CreateProjectRequest\",\n    \"CreateRequirementRequest\": \"uipath:CreateRequirementRequest\",\n    \"CreateTestCaseRequest\": \"uipath:CreateTestCaseRequest\",\n    \"CreateTestSetRequest\": \"uipath:CreateTestSetRequest\",\n    \"ProjectListResponse\": \"uipath:ProjectListResponse\",\n    \"Project\": \"uipath:Project\",\n    \"RequirementListResponse\": \"uipath:RequirementListResponse\",\n    \"Requirement\": \"uipath:Requirement\",\n    \"TestCaseListResponse\": \"uipath:TestCaseListResponse\",\n    \"TestCase\": \"uipath:TestCase\",\n    \"TestExecutionListResponse\": \"uipath:TestExecutionListResponse\",\n    \"TestExecution\": \"uipath:TestExecution\",\n    \"TestSetListResponse\": \"uipath:TestSetListResponse\"\
  ,\n    \"TestSet\": \"uipath:TestSet\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"externalId\": {\n      \"@id\": \"uipath:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"uipath:labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"uipath:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"uipath:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"uipath:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projects\": {\n      \"@id\": \"uipath:projects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"uipath:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdBy\": {\n      \"@id\": \"uipath:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdOn\": {\n      \"@id\"\
  : \"uipath:createdOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"testCaseCount\": {\n      \"@id\": \"uipath:testCaseCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requirementCount\": {\n      \"@id\": \"uipath:requirementCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requirements\": {\n      \"@id\": \"uipath:requirements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uipath:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linkedTestCaseCount\": {\n      \"@id\": \"uipath:linkedTestCaseCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"testCases\": {\n      \"@id\": \"uipath:testCases\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automationStatus\": {\n      \"@id\": \"uipath:automationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executions\": {\n      \"@id\": \"uipath:executions\",\n      \"@container\": \"@set\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"testSetId\": {\n      \"@id\": \"uipath:testSetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"testSetName\": {\n      \"@id\": \"uipath:testSetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedOn\": {\n      \"@id\": \"uipath:startedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishedOn\": {\n      \"@id\": \"uipath:finishedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalTestCases\": {\n      \"@id\": \"uipath:totalTestCases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passedTestCases\": {\n      \"@id\": \"uipath:passedTestCases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failedTestCases\": {\n      \"@id\": \"uipath:failedTestCases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"blockedTestCases\": {\n      \"@id\": \"uipath:blockedTestCases\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"testSets\": {\n      \"@id\": \"uipath:testSets\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-test-manager-context.jsonld
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
