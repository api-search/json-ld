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
