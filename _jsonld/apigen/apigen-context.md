---
class_count: 29
classes:
- id
- type
- Project
- Api
- Endpoint
- Schema
- Connector
- Deployment
- Test
- TestRun
- User
- Token
- name
- description
- url
- version
- status
- environment
- method
- path
- generationSource
- prompt
- requestSchema
- responseSchema
- region
- replicas
- scopes
- email
- organization
context_file: json-ld/apigen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/json-ld/apigen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apigen from APIGen.
layout: jsonld
name: Apigen Context
namespaces:
- prefix: apigen
  uri: https://api.apigen.com/vocab#
properties:
- container: ''
  name: projectId
  type: reference
- container: ''
  name: apiId
  type: reference
- container: ''
  name: endpointId
  type: reference
- container: ''
  name: connectorId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: deployedBy
  type: reference
- container: ''
  name: specUrl
  type: reference
- container: ''
  name: createdAt
  type: DateTime
- container: ''
  name: updatedAt
  type: DateTime
- container: ''
  name: expiresAt
  type: DateTime
property_count: 10
provider_name: APIGen
provider_slug: apigen
slug: apigen-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apigen\": \"https://api.apigen.com/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Project\": \"apigen:Project\",\n    \"Api\": \"apigen:Api\",\n    \"Endpoint\": \"apigen:Endpoint\",\n    \"Schema\": \"apigen:Schema\",\n    \"Connector\": \"apigen:Connector\",\n    \"Deployment\": \"apigen:Deployment\",\n    \"Test\": \"apigen:Test\",\n    \"TestRun\": \"apigen:TestRun\",\n    \"User\": \"Person\",\n    \"Token\": \"apigen:Token\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"version\": \"softwareVersion\",\n    \"status\": \"apigen:status\",\n    \"environment\": \"apigen:environment\",\n    \"method\": \"apigen:httpMethod\",\n    \"path\": \"apigen:urlPath\",\n    \"projectId\": {\n      \"@id\": \"apigen:project\",\n      \"@type\": \"@id\"\n    },\n    \"apiId\": {\n      \"@id\": \"apigen:api\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"endpointId\": {\n      \"@id\": \"apigen:endpoint\",\n      \"@type\": \"@id\"\n    },\n    \"connectorId\": {\n      \"@id\": \"apigen:connector\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"apigen:owner\",\n      \"@type\": \"@id\"\n    },\n    \"deployedBy\": {\n      \"@id\": \"apigen:deployedBy\",\n      \"@type\": \"@id\"\n    },\n    \"generationSource\": \"apigen:generationSource\",\n    \"prompt\": \"apigen:prompt\",\n    \"specUrl\": {\n      \"@id\": \"apigen:specUrl\",\n      \"@type\": \"@id\"\n    },\n    \"requestSchema\": \"apigen:requestSchema\",\n    \"responseSchema\": \"apigen:responseSchema\",\n    \"region\": \"apigen:region\",\n    \"replicas\": \"apigen:replicas\",\n    \"scopes\": \"apigen:scopes\",\n    \"email\": \"email\",\n    \"organization\": \"memberOf\",\n    \"createdAt\": {\n      \"@id\": \"dateCreated\",\n      \"@type\": \"DateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dateModified\",\n      \"@type\": \"\
  DateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"expires\",\n      \"@type\": \"DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apigen/refs/heads/main/json-ld/apigen-context.jsonld
tags:
- Code
- Documentation
- Generation
- Open Source
- PHP
- JSON-LD
- Linked Data
- Semantic Web
---
