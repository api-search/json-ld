---
class_count: 0
classes: []
context_file: json-ld/azure-devops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/json-ld/azure-devops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Devops from Azure DevOps.
layout: jsonld
name: Azure Devops Context
namespaces:
- prefix: ado
  uri: https://dev.azure.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: WorkItem
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: PipelineRun
  type: ''
- container: ''
  name: Repository
  type: ''
property_count: 4
provider_name: Azure DevOps
provider_slug: azure-devops
slug: azure-devops-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ado\": \"https://dev.azure.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"WorkItem\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\"},\n        \"rev\": {\"@id\": \"ado:revision\", \"@type\": \"xsd:integer\"},\n        \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n        \"fields\": {\n          \"@id\": \"ado:fields\",\n          \"@context\": {\n            \"System.Id\": {\"@id\": \"schema:identifier\"},\n            \"System.Title\": {\"@id\": \"schema:name\"},\n            \"System.WorkItemType\": {\"@id\": \"schema:additionalType\"},\n            \"System.State\": {\"@id\": \"ado:workItemState\"},\n            \"System.AssignedTo\": {\"@id\": \"schema:assignee\"},\n            \"System.CreatedDate\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"\
  },\n            \"System.CreatedBy\": {\"@id\": \"schema:creator\"},\n            \"System.ChangedDate\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n            \"System.TeamProject\": {\"@id\": \"schema:isPartOf\"},\n            \"System.AreaPath\": {\"@id\": \"ado:areaPath\"},\n            \"System.IterationPath\": {\"@id\": \"ado:iterationPath\"},\n            \"System.Description\": {\"@id\": \"schema:description\"},\n            \"System.Tags\": {\"@id\": \"schema:keywords\"},\n            \"Microsoft.VSTS.Common.Priority\": {\"@id\": \"schema:priority\", \"@type\": \"xsd:integer\"}\n          }\n        },\n        \"relations\": {\"@id\": \"schema:relatedLink\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"url\": {\"@id\": \"schema:url\"}\n      }\n    },\n\n\
  \    \"PipelineRun\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"state\": {\"@id\": \"ado:runState\"},\n        \"result\": {\"@id\": \"ado:runResult\"},\n        \"createdDate\": {\"@id\": \"schema:startTime\", \"@type\": \"xsd:dateTime\"},\n        \"finishedDate\": {\"@id\": \"schema:endTime\", \"@type\": \"xsd:dateTime\"}\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"id\": {\"@id\": \"schema:identifier\"},\n        \"name\": {\"@id\": \"schema:name\"},\n        \"url\": {\"@id\": \"schema:codeRepository\", \"@type\": \"@id\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/json-ld/azure-devops-context.jsonld
tags:
- Azure
- CI/CD
- DevOps
- Pipelines
- Work Items
- JSON-LD
- Linked Data
- Semantic Web
---
