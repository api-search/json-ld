---
api_specs:
- filename: workato-developer-api-openapi.yml
  format: yaml
  label: Workato
  slug: workato
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/openapi/workato-developer-api-openapi.yml
- filename: workato-event-streams-openapi.yml
  format: yaml
  label: Workato Event Streams Public API
  slug: event-streams-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/openapi/workato-event-streams-openapi.yml
- filename: workato-mcp-server-openapi.yml
  format: yaml
  label: Workato MCP Server API
  slug: mcp-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/openapi/workato-mcp-server-openapi.yml
class_count: 0
classes: []
context_file: json-ld/workato-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/json-ld/workato-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workato from Workato.
layout: jsonld
name: Workato Context
namespaces:
- prefix: workato
  uri: https://www.workato.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Recipe
  type: ''
- container: ''
  name: Genie
  type: ''
- container: ''
  name: Skill
  type: ''
- container: ''
  name: KnowledgeBase
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: McpServer
  type: ''
- container: ''
  name: McpTool
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: DataTable
  type: ''
- container: ''
  name: EventTopic
  type: ''
property_count: 10
provider_name: Workato
provider_slug: workato
slug: workato-context
source_filename: workato-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workato\": \"https://www.workato.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Recipe\": {\n      \"@id\": \"workato:Recipe\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"running\": {\n          \"@id\": \"workato:running\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"trigger_application\": {\n          \"@id\": \"workato:triggerApplication\"\n        },\n        \"action_applications\": {\n          \"@id\": \"workato:actionApplications\",\n          \"@container\": \"@set\"\n        },\n        \"stop_cause\"\
  : {\n          \"@id\": \"workato:stopCause\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"stopped_at\": {\n          \"@id\": \"workato:stoppedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"job_succeeded_count\": {\n          \"@id\": \"workato:jobSucceededCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"job_failed_count\": {\n          \"@id\": \"workato:jobFailedCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"version_no\": {\n          \"@id\": \"workato:versionNumber\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Genie\": {\n      \"@id\": \"workato:Genie\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n\
  \        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"state\": {\n          \"@id\": \"workato:state\"\n        },\n        \"instructions\": {\n          \"@id\": \"workato:instructions\"\n        },\n        \"ai_provider\": {\n          \"@id\": \"workato:aiProvider\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"skills\": {\n          \"@id\": \"workato:hasSkill\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"knowledge_bases\": {\n          \"@id\": \"workato:hasKnowledgeBase\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\
  \n    \"Skill\": {\n      \"@id\": \"workato:Skill\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"recipe_id\": {\n          \"@id\": \"workato:recipeId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"KnowledgeBase\": {\n      \"@id\": \"workato:KnowledgeBase\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\
  \n        },\n        \"source_type\": {\n          \"@id\": \"workato:sourceType\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"data_sources\": {\n          \"@id\": \"workato:hasDataSource\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"workato:DataSource\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"source_type\": {\n          \"@id\": \"workato:sourceType\"\n        },\n        \"connection_id\": {\n          \"@id\": \"workato:connectionId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sync_frequency\": {\n          \"@id\": \"\
  workato:syncFrequency\"\n        },\n        \"config\": {\n          \"@id\": \"workato:config\"\n        }\n      }\n    },\n\n    \"McpServer\": {\n      \"@id\": \"workato:McpServer\",\n      \"@context\": {\n        \"handle\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"mcp_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"authentication_method\": {\n          \"@id\": \"workato:authenticationMethod\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tools\": {\n          \"@id\": \"workato:hasTool\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"McpTool\": {\n      \"@id\": \"workato:McpTool\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"trigger_application\": {\n          \"@id\": \"workato:triggerApplication\"\n        }\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"workato:Connection\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"provider\": {\n          \"@id\": \"schema:provider\"\n        },\n        \"authorized\": {\n          \"@id\": \"workato:authorized\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataTable\": {\n      \"@id\": \"workato:DataTable\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"folder_id\": {\n          \"@id\": \"workato:folderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"schema\": {\n          \"@id\": \"workato:tableSchema\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EventTopic\": {\n      \"@id\": \"workato:EventTopic\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n     \
  \   },\n        \"schema\": {\n          \"@id\": \"workato:topicSchema\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/json-ld/workato-context.jsonld
tags:
- Agentic
- API Management
- Automation
- B2B
- Embedded iPaaS
- Enterprise
- Integration
- iPaaS
- Orchestration
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
