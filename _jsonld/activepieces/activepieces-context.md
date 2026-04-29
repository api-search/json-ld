---
class_count: 25
classes:
- User
- UpdateUserRequest
- UpdateFolderRequest
- ConnectionList
- Piece
- CreateProjectRequest
- QueueMetrics
- Connection
- FlowRunList
- FolderList
- UpsertConnectionRequest
- Folder
- UserList
- Template
- FlowRun
- UpdateProjectRequest
- CreateTemplateRequest
- TemplateList
- ProjectList
- Flow
- Project
- CreateFlowRequest
- CreateFolderRequest
- FlowList
- UpdateFlowRequest
context_file: json-ld/activepieces-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/json-ld/activepieces-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Activepieces from Activepieces.
layout: jsonld
name: Activepieces Context
namespaces:
- prefix: activepieces
  uri: https://www.activepieces.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: email
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: platformRole
  type: string
- container: ''
  name: displayName
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: next
  type: string
- container: ''
  name: previous
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: iconUrl
  type: reference
- container: set
  name: categories
  type: string
- container: set
  name: queues
  type: string
- container: ''
  name: pieceName
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: flowId
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: finishTime
  type: dateTime
- container: ''
  name: duration
  type: integer
- container: ''
  name: notifyStatus
  type: string
- container: ''
  name: externalId
  type: string
- container: ''
  name: folderId
  type: string
- container: ''
  name: publishedVersionId
  type: string
- container: ''
  name: ownerId
  type: string
- container: ''
  name: platformId
  type: string
- container: ''
  name: templateId
  type: string
- container: ''
  name: metadata
  type: string
property_count: 35
provider_name: Activepieces
provider_slug: activepieces
slug: activepieces-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"activepieces\": \"https://www.activepieces.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"User\": \"activepieces:User\",\n    \"UpdateUserRequest\": \"activepieces:UpdateUserRequest\",\n    \"UpdateFolderRequest\": \"activepieces:UpdateFolderRequest\",\n    \"ConnectionList\": \"activepieces:ConnectionList\",\n    \"Piece\": \"activepieces:Piece\",\n    \"CreateProjectRequest\": \"activepieces:CreateProjectRequest\",\n    \"QueueMetrics\": \"activepieces:QueueMetrics\",\n    \"Connection\": \"activepieces:Connection\",\n    \"FlowRunList\": \"activepieces:FlowRunList\",\n    \"FolderList\": \"activepieces:FolderList\",\n    \"UpsertConnectionRequest\": \"activepieces:UpsertConnectionRequest\",\n    \"Folder\": \"activepieces:Folder\",\n    \"UserList\": \"activepieces:UserList\",\n    \"Template\": \"activepieces:Template\"\
  ,\n    \"FlowRun\": \"activepieces:FlowRun\",\n    \"UpdateProjectRequest\": \"activepieces:UpdateProjectRequest\",\n    \"CreateTemplateRequest\": \"activepieces:CreateTemplateRequest\",\n    \"TemplateList\": \"activepieces:TemplateList\",\n    \"ProjectList\": \"activepieces:ProjectList\",\n    \"Flow\": \"activepieces:Flow\",\n    \"Project\": \"activepieces:Project\",\n    \"CreateFlowRequest\": \"activepieces:CreateFlowRequest\",\n    \"CreateFolderRequest\": \"activepieces:CreateFolderRequest\",\n    \"FlowList\": \"activepieces:FlowList\",\n    \"UpdateFlowRequest\": \"activepieces:UpdateFlowRequest\",\n    \"id\": {\n      \"@id\": \"activepieces:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"firstName\": {\n      \"@id\": \"activepieces:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"activepieces:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"activepieces:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformRole\": {\n      \"@id\": \"activepieces:platformRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"activepieces:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"activepieces:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next\": {\n      \"@id\": \"activepieces:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previous\": {\n      \"@id\": \"activepieces:previous\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n     \
  \ \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"activepieces:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iconUrl\": {\n      \"@id\": \"activepieces:iconUrl\",\n      \"@type\": \"@id\"\n    },\n    \"categories\": {\n      \"@id\": \"activepieces:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queues\": {\n      \"@id\": \"activepieces:queues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pieceName\": {\n      \"@id\": \"activepieces:pieceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"activepieces:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"activepieces:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"activepieces:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"activepieces:tags\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flowId\": {\n      \"@id\": \"activepieces:flowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"activepieces:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishTime\": {\n      \"@id\": \"activepieces:finishTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"activepieces:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notifyStatus\": {\n      \"@id\": \"activepieces:notifyStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"activepieces:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"folderId\": {\n      \"@id\": \"activepieces:folderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedVersionId\": {\n      \"@id\": \"activepieces:publishedVersionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ownerId\": {\n      \"@id\": \"activepieces:ownerId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"platformId\": {\n      \"@id\": \"activepieces:platformId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateId\": {\n      \"@id\": \"activepieces:templateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"activepieces:metadata\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/activepieces/refs/heads/main/json-ld/activepieces-context.jsonld
tags:
- Automation
- No-Code
- Open Source
- Workflow
- AI Agents
- MCP
- JSON-LD
- Linked Data
- Semantic Web
---
