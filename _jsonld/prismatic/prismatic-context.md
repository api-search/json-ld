---
api_specs:
- filename: prismatic-graphql-api-openapi.yml
  format: yaml
  label: Prismatics GraphQL API
  slug: prismatics-graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/openapi/prismatic-graphql-api-openapi.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/prismatic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/json-ld/prismatic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Prismatic from Prismatic.
layout: jsonld
name: Prismatic Context
namespaces:
- prefix: prismatic
  uri: https://prismatic.io/docs/api/schema/
properties:
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Integration
  type: ''
- container: ''
  name: Instance
  type: ''
- container: ''
  name: Component
  type: ''
- container: ''
  name: Flow
  type: ''
- container: ''
  name: ConfigVariable
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: AlertMonitor
  type: ''
- container: ''
  name: Execution
  type: ''
property_count: 9
provider_name: Prismatic
provider_slug: prismatic
slug: prismatic-context
source_filename: prismatic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"prismatic\": \"https://prismatic.io/docs/api/schema/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Customer\": {\n      \"@id\": \"prismatic:Customer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"externalId\": \"schema:identifier\",\n        \"avatarUrl\": \"schema:image\",\n        \"labels\": \"schema:keywords\",\n        \"allowEmbeddedDesigner\": \"prismatic:allowEmbeddedDesigner\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Integration\": {\n      \"@id\": \"prismatic:Integration\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"labels\": \"schema:keywords\",\n        \"overview\": \"schema:abstract\",\n        \"versionNumber\"\
  : \"schema:version\",\n        \"isCodeNative\": \"prismatic:isCodeNative\",\n        \"marketplaceConfiguration\": \"prismatic:marketplaceConfiguration\",\n        \"flows\": \"prismatic:flows\",\n        \"instances\": \"prismatic:instances\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Instance\": {\n      \"@id\": \"prismatic:Instance\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"prismatic:enabled\",\n        \"deployed\": \"prismatic:deployed\",\n        \"needsDeploy\": \"prismatic:needsDeploy\",\n        \"customer\": \"prismatic:customer\",\n        \"integration\": \"prismatic:integration\",\n        \"configVariables\": \"prismatic:configVariables\",\n        \"flowConfigs\": \"prismatic:flowConfigs\",\n        \"labels\": \"schema:keywords\",\n        \"lastDeployedAt\": \"prismatic:lastDeployedAt\",\n        \"\
  createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Component\": {\n      \"@id\": \"prismatic:Component\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"label\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"isPublic\": \"prismatic:isPublic\",\n        \"authorizationRequired\": \"prismatic:authorizationRequired\",\n        \"iconUrl\": \"schema:image\",\n        \"actions\": \"schema:potentialAction\",\n        \"triggers\": \"prismatic:triggers\",\n        \"dataSources\": \"prismatic:dataSources\",\n        \"connections\": \"prismatic:connections\",\n        \"versionNumber\": \"schema:version\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Flow\": {\n      \"@id\": \"prismatic:Flow\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n  \
  \      \"description\": \"schema:description\",\n        \"stableKey\": \"schema:identifier\",\n        \"isSynchronous\": \"prismatic:isSynchronous\",\n        \"steps\": \"prismatic:steps\",\n        \"endpointSecurityType\": \"prismatic:endpointSecurityType\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"ConfigVariable\": {\n      \"@id\": \"prismatic:ConfigVariable\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"description\": \"schema:description\",\n        \"dataType\": \"prismatic:dataType\",\n        \"defaultValue\": \"schema:defaultValue\",\n        \"value\": \"schema:value\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"prismatic:User\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"avatarUrl\": \"schema:image\"\
  ,\n        \"externalId\": \"schema:identifier\",\n        \"role\": \"schema:roleName\",\n        \"customer\": \"prismatic:customer\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"AlertMonitor\": {\n      \"@id\": \"prismatic:AlertMonitor\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"triggered\": \"prismatic:triggered\",\n        \"triggerType\": \"prismatic:triggerType\",\n        \"instance\": \"prismatic:instance\",\n        \"createdAt\": \"schema:dateCreated\",\n        \"updatedAt\": \"schema:dateModified\"\n      }\n    },\n    \"Execution\": {\n      \"@id\": \"prismatic:Execution\",\n      \"@context\": {\n        \"status\": \"schema:actionStatus\",\n        \"instance\": \"prismatic:instance\",\n        \"flow\": \"prismatic:flow\",\n        \"stepResults\": \"prismatic:stepResults\",\n        \"startedAt\": \"schema:startTime\",\n        \"endedAt\": \"schema:endTime\"\n\
  \      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/prismatic/refs/heads/main/json-ld/prismatic-context.jsonld
tags:
- Embedded iPaaS
- Integrations
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
