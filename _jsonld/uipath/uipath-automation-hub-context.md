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
class_count: 18
classes:
- AddUserRequest
- AppInventoryListResponse
- Application
- AutomationListResponse
- Automation
- BenefitData
- Collaborator
- CreateAutomationIdeaRequest
- EditUserRequest
- PhaseCount
- PipelineData
- Role
- UpdateAutomationRequest
- UserListResponse
- User
- email
- name
- description
context_file: json-ld/uipath-automation-hub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-automation-hub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Automation Hub from UiPath.
layout: jsonld
name: Uipath Automation Hub Context
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
  name: role
  type: string
- container: ''
  name: totalCount
  type: integer
- container: set
  name: applications
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: vendor
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: set
  name: automations
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submittedBy
  type: string
- container: ''
  name: submittedDate
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: estimatedBenefit
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: estimatedTimeSavingsPerYear
  type: decimal
- container: ''
  name: estimatedFTESavings
  type: decimal
- container: ''
  name: estimatedCostSavingsPerYear
  type: decimal
- container: ''
  name: userId
  type: integer
- container: ''
  name: isActive
  type: boolean
- container: ''
  name: count
  type: integer
- container: set
  name: phases
  type: string
- container: set
  name: users
  type: string
property_count: 24
provider_name: UiPath
provider_slug: uipath
slug: uipath-automation-hub-context
source_filename: uipath-automation-hub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddUserRequest\": \"uipath:AddUserRequest\",\n    \"AppInventoryListResponse\": \"uipath:AppInventoryListResponse\",\n    \"Application\": \"uipath:Application\",\n    \"AutomationListResponse\": \"uipath:AutomationListResponse\",\n    \"Automation\": \"uipath:Automation\",\n    \"BenefitData\": \"uipath:BenefitData\",\n    \"Collaborator\": \"uipath:Collaborator\",\n    \"CreateAutomationIdeaRequest\": \"uipath:CreateAutomationIdeaRequest\",\n    \"EditUserRequest\": \"uipath:EditUserRequest\",\n    \"PhaseCount\": \"uipath:PhaseCount\",\n    \"PipelineData\": \"uipath:PipelineData\",\n    \"Role\": \"uipath:Role\",\n    \"UpdateAutomationRequest\": \"uipath:UpdateAutomationRequest\",\n    \"UserListResponse\": \"uipath:UserListResponse\"\
  ,\n    \"User\": \"uipath:User\",\n    \"email\": \"schema:email\",\n    \"role\": {\n      \"@id\": \"uipath:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"uipath:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"applications\": {\n      \"@id\": \"uipath:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"uipath:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"vendor\": {\n      \"@id\": \"uipath:vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"uipath:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"page\": {\n      \"@id\": \"uipath:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"uipath:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"automations\": {\n      \"@id\": \"uipath:automations\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phase\": {\n      \"@id\": \"uipath:phase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"uipath:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedBy\": {\n      \"@id\": \"uipath:submittedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedDate\": {\n      \"@id\": \"uipath:submittedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"uipath:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"estimatedBenefit\": {\n      \"@id\": \"uipath:estimatedBenefit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"uipath:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedTimeSavingsPerYear\": {\n      \"@id\": \"uipath:estimatedTimeSavingsPerYear\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"estimatedFTESavings\": {\n\
  \      \"@id\": \"uipath:estimatedFTESavings\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"estimatedCostSavingsPerYear\": {\n      \"@id\": \"uipath:estimatedCostSavingsPerYear\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"userId\": {\n      \"@id\": \"uipath:userId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isActive\": {\n      \"@id\": \"uipath:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"count\": {\n      \"@id\": \"uipath:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"phases\": {\n      \"@id\": \"uipath:phases\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"uipath:users\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-automation-hub-context.jsonld
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
