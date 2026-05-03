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
class_count: 25
classes:
- BatchPublishRequest
- BatchPublishResponse
- ConsumeRequest
- ConsumeResponse
- DataSource
- DataTable
- DataTableColumn
- DataTableInput
- Genie
- GenieInput
- KnowledgeBase
- KnowledgeBaseInput
- McpServer
- McpServerInput
- Message
- PublishResponse
- Recipe
- RecipeInput
- RecipeVersion
- ServerPolicy
- Skill
- Tool
- UserGroup
- Workato Genie
- Workato Recipe
context_file: json-ld/workato-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workato/refs/heads/main/json-ld/workato-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workato from Workato.
layout: jsonld
name: Workato Context
namespaces:
- prefix: workato
  uri: https://www.workato.com/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: schema
  type: string
- container: set
  name: actionApplications
  type: string
- container: ''
  name: afterMessageId
  type: string
- container: ''
  name: aiProvider
  type: string
- container: ''
  name: authenticationMethod
  type: string
- container: ''
  name: batchSize
  type: integer
- container: ''
  name: code
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: config
  type: string
- container: ''
  name: connectionId
  type: integer
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: customOauthKeyId
  type: integer
- container: set
  name: dataSources
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: folderId
  type: integer
- container: ''
  name: handle
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: instructions
  type: string
- container: set
  name: ipAllowlist
  type: string
- container: set
  name: ipDenylist
  type: string
- container: ''
  name: isPartialError
  type: boolean
- container: ''
  name: jobFailedCount
  type: integer
- container: ''
  name: jobSucceededCount
  type: integer
- container: set
  name: knowledgeBases
  type: string
- container: ''
  name: lastRunAt
  type: dateTime
- container: ''
  name: matrix
  type: reference
- container: ''
  name: mcpUrl
  type: reference
- container: ''
  name: messageId
  type: string
- container: ''
  name: messageIds
  type: reference
- container: set
  name: messages
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: payload
  type: reference
- container: set
  name: payloads
  type: ''
- container: ''
  name: quotaLimit
  type: reference
- container: ''
  name: rateLimit
  type: reference
- container: ''
  name: recipe
  type: reference
- container: ''
  name: recipeId
  type: integer
- container: ''
  name: required
  type: boolean
- container: ''
  name: running
  type: boolean
- container: ''
  name: sharedAccountId
  type: integer
- container: ''
  name: sinceTime
  type: dateTime
- container: set
  name: skills
  type: string
- container: ''
  name: sourceType
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: stopCause
  type: string
- container: ''
  name: stoppedAt
  type: dateTime
- container: ''
  name: time
  type: dateTime
- container: ''
  name: timeoutSecs
  type: integer
- container: ''
  name: triggerApplication
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: ''
- container: set
  name: userGroups
  type: string
- container: ''
  name: versionNo
  type: integer
- container: ''
  name: McpTool
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: EventTopic
  type: ''
property_count: 56
provider_name: Workato
provider_slug: workato
slug: workato-context
source_filename: workato-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"workato\": \"https://www.workato.com/schema/\",\n    \"schema\": {\n      \"@id\": \"workato:schema\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchPublishRequest\": \"workato:BatchPublishRequest\",\n    \"BatchPublishResponse\": \"workato:BatchPublishResponse\",\n    \"ConsumeRequest\": \"workato:ConsumeRequest\",\n    \"ConsumeResponse\": \"workato:ConsumeResponse\",\n    \"DataSource\": \"workato:DataSource\",\n    \"DataTable\": \"workato:DataTable\",\n    \"DataTableColumn\": \"workato:DataTableColumn\",\n    \"DataTableInput\": \"workato:DataTableInput\",\n    \"Genie\": \"workato:Genie\",\n    \"GenieInput\": \"workato:GenieInput\",\n    \"KnowledgeBase\": \"workato:KnowledgeBase\",\n    \"KnowledgeBaseInput\": \"workato:KnowledgeBaseInput\",\n    \"McpServer\": \"workato:McpServer\"\
  ,\n    \"McpServerInput\": \"workato:McpServerInput\",\n    \"Message\": \"workato:Message\",\n    \"PublishResponse\": \"workato:PublishResponse\",\n    \"Recipe\": \"workato:Recipe\",\n    \"RecipeInput\": \"workato:RecipeInput\",\n    \"RecipeVersion\": \"workato:RecipeVersion\",\n    \"ServerPolicy\": \"workato:ServerPolicy\",\n    \"Skill\": \"workato:Skill\",\n    \"Tool\": \"workato:Tool\",\n    \"UserGroup\": \"workato:UserGroup\",\n    \"Workato Genie\": \"workato:Workato Genie\",\n    \"Workato Recipe\": \"workato:Workato Recipe\",\n    \"actionApplications\": {\n      \"@id\": \"workato:action_applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"afterMessageId\": {\n      \"@id\": \"workato:after_message_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aiProvider\": {\n      \"@id\": \"workato:ai_provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationMethod\": {\n      \"@id\": \"workato:authentication_method\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"batchSize\": {\n      \"@id\": \"workato:batch_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"workato:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"workato:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"workato:config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionId\": {\n      \"@id\": \"workato:connection_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\n    },\n    \"customOauthKeyId\": {\n      \"@id\": \"workato:custom_oauth_key_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataSources\": {\n      \"@id\": \"workato:data_sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"folderId\": {\n      \"@id\": \"workato:folder_id\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"handle\": {\n      \"@id\": \"workato:handle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"workato:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"instructions\": {\n      \"@id\": \"workato:instructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAllowlist\": {\n      \"@id\": \"workato:ip_allowlist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipDenylist\": {\n      \"@id\": \"workato:ip_denylist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPartialError\": {\n      \"@id\": \"workato:is_partial_error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"jobFailedCount\": {\n      \"@id\": \"workato:job_failed_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobSucceededCount\": {\n      \"@id\": \"workato:job_succeeded_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"knowledgeBases\": {\n     \
  \ \"@id\": \"workato:knowledge_bases\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRunAt\": {\n      \"@id\": \"workato:last_run_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"matrix\": {\n      \"@id\": \"workato:matrix\",\n      \"@type\": \"@id\"\n    },\n    \"mcpUrl\": {\n      \"@id\": \"workato:mcp_url\",\n      \"@type\": \"@id\"\n    },\n    \"messageId\": {\n      \"@id\": \"workato:message_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageIds\": {\n      \"@id\": \"workato:message_ids\",\n      \"@type\": \"@id\"\n    },\n    \"messages\": {\n      \"@id\": \"workato:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"payload\": {\n      \"@id\": \"workato:payload\",\n      \"@type\": \"@id\"\n    },\n    \"payloads\": {\n      \"@id\": \"workato:payloads\",\n      \"@container\": \"@set\"\n    },\n    \"quotaLimit\"\
  : {\n      \"@id\": \"workato:quota_limit\",\n      \"@type\": \"@id\"\n    },\n    \"rateLimit\": {\n      \"@id\": \"workato:rate_limit\",\n      \"@type\": \"@id\"\n    },\n    \"recipe\": {\n      \"@id\": \"workato:recipe\",\n      \"@type\": \"@id\"\n    },\n    \"recipeId\": {\n      \"@id\": \"workato:recipe_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"required\": {\n      \"@id\": \"workato:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"running\": {\n      \"@id\": \"workato:running\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sharedAccountId\": {\n      \"@id\": \"workato:shared_account_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sinceTime\": {\n      \"@id\": \"workato:since_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"skills\": {\n      \"@id\": \"workato:skills\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceType\": {\n      \"@id\": \"workato:source_type\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"workato:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopCause\": {\n      \"@id\": \"workato:stop_cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stoppedAt\": {\n      \"@id\": \"workato:stopped_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"time\": {\n      \"@id\": \"workato:time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeoutSecs\": {\n      \"@id\": \"workato:timeout_secs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"triggerApplication\": {\n      \"@id\": \"workato:trigger_application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"workato:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\"\n    },\n    \"userGroups\": {\n      \"@id\": \"workato:user_groups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionNo\": {\n      \"@id\": \"workato:version_no\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"McpTool\": {\n      \"@id\": \"workato:McpTool\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"trigger_application\": {\n          \"@id\": \"workato:triggerApplication\"\n        }\n      }\n    },\n    \"Connection\": {\n      \"@id\": \"workato:Connection\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"provider\": {\n          \"@id\": \"schema:provider\"\n        },\n        \"authorized\": {\n          \"@id\": \"workato:authorized\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n    \"EventTopic\": {\n      \"@id\": \"workato:EventTopic\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"schema\": {\n          \"@id\": \"workato:topicSchema\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
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
