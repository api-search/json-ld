---
class_count: 17
classes:
- Authorization
- BootstrapConfiguration
- CodeRepository
- InputDescriptor
- InputValue
- OperationDisplayValue
- OrganizationReference
- Pipeline
- PipelineListResult
- PipelineProperties
- PipelineTemplate
- PipelineTemplateDefinition
- PipelineTemplateDefinitionListResult
- PipelineUpdateParameters
- ProjectReference
- description
- name
context_file: json-ld/azure-dev-ops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/json-ld/azure-dev-ops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Dev Ops from Azure DevOps.
layout: jsonld
name: Azure Dev Ops Context
namespaces:
- prefix: azuredevops
  uri: https://azure.microsoft.com/azure-dev-ops/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: authorizationType
  type: string
- container: ''
  name: parameters
  type: reference
- container: ''
  name: repository
  type: string
- container: ''
  name: template
  type: string
- container: ''
  name: authorization
  type: string
- container: ''
  name: defaultBranch
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: repositoryType
  type: string
- container: set
  name: possibleValues
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: displayValue
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: nextLink
  type: string
- container: ''
  name: bootstrapConfiguration
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: pipelineId
  type: integer
- container: ''
  name: project
  type: string
- container: set
  name: inputs
  type: string
- container: ''
  name: tags
  type: reference
property_count: 23
provider_name: Azure DevOps
provider_slug: azure-dev-ops
slug: azure-dev-ops-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azuredevops\": \"https://azure.microsoft.com/azure-dev-ops/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Authorization\": \"azuredevops:Authorization\",\n    \"BootstrapConfiguration\": \"azuredevops:BootstrapConfiguration\",\n    \"CodeRepository\": \"azuredevops:CodeRepository\",\n    \"InputDescriptor\": \"azuredevops:InputDescriptor\",\n    \"InputValue\": \"azuredevops:InputValue\",\n    \"OperationDisplayValue\": \"azuredevops:OperationDisplayValue\",\n    \"OrganizationReference\": \"azuredevops:OrganizationReference\",\n    \"Pipeline\": \"azuredevops:Pipeline\",\n    \"PipelineListResult\": \"azuredevops:PipelineListResult\",\n    \"PipelineProperties\": \"azuredevops:PipelineProperties\",\n    \"PipelineTemplate\": \"azuredevops:PipelineTemplate\",\n    \"PipelineTemplateDefinition\": \"azuredevops:PipelineTemplateDefinition\"\
  ,\n    \"PipelineTemplateDefinitionListResult\": \"azuredevops:PipelineTemplateDefinitionListResult\",\n    \"PipelineUpdateParameters\": \"azuredevops:PipelineUpdateParameters\",\n    \"ProjectReference\": \"azuredevops:ProjectReference\",\n    \"authorizationType\": {\n      \"@id\": \"azuredevops:authorizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"azuredevops:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"repository\": {\n      \"@id\": \"azuredevops:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"template\": {\n      \"@id\": \"azuredevops:template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorization\": {\n      \"@id\": \"azuredevops:authorization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultBranch\": {\n      \"@id\": \"azuredevops:defaultBranch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"azuredevops:id\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"properties\": {\n      \"@id\": \"azuredevops:properties\",\n      \"@type\": \"@id\"\n    },\n    \"repositoryType\": {\n      \"@id\": \"azuredevops:repositoryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"possibleValues\": {\n      \"@id\": \"azuredevops:possibleValues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azuredevops:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayValue\": {\n      \"@id\": \"azuredevops:displayValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azuredevops:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"azuredevops:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"azuredevops:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"azuredevops:resource\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextLink\": {\n      \"@id\": \"azuredevops:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapConfiguration\": {\n      \"@id\": \"azuredevops:bootstrapConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"azuredevops:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineId\": {\n      \"@id\": \"azuredevops:pipelineId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"project\": {\n      \"@id\": \"azuredevops:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputs\": {\n      \"@id\": \"azuredevops:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"azuredevops:tags\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/json-ld/azure-dev-ops-context.jsonld
tags:
- Azure
- CI/CD
- DevOps
- Project Management
- Version Control
- JSON-LD
- Linked Data
- Semantic Web
---
