---
api_specs:
- filename: anthropic-messages-api-openapi.yml
  format: yaml
  label: Anthropic Messages API
  slug: anthropic-messages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/anthropic/refs/heads/main/openapi/anthropic-messages-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/anthropic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/anthropic/refs/heads/main/json-ld/anthropic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Anthropic from Anthropic.
layout: jsonld
name: Anthropic Context
namespaces:
- prefix: anthropic
  uri: https://api.anthropic.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: MessageRequest
  type: ''
- container: ''
  name: MessageParam
  type: ''
- container: ''
  name: TextBlock
  type: ''
- container: ''
  name: ImageBlock
  type: ''
- container: ''
  name: DocumentBlock
  type: ''
- container: ''
  name: ToolDefinition
  type: ''
- container: ''
  name: ToolUseBlock
  type: ''
- container: ''
  name: ToolResultBlock
  type: ''
- container: ''
  name: ToolChoice
  type: ''
- container: ''
  name: ThinkingBlock
  type: ''
- container: ''
  name: ThinkingConfig
  type: ''
- container: ''
  name: Usage
  type: ''
- container: ''
  name: Citation
  type: ''
- container: ''
  name: CacheControl
  type: ''
- container: ''
  name: Metadata
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 18
provider_name: Anthropic
provider_slug: anthropic
slug: anthropic-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"anthropic\": \"https://api.anthropic.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"Message\": {\n      \"@id\": \"anthropic:Message\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"anthropic:Message/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"anthropic:Message/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"anthropic:Message/role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"anthropic:Message/content\",\n          \"@container\": \"@list\"\n        },\n        \"model\": {\n          \"@id\": \"anthropic:Message/model\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"stop_reason\": {\n          \"@id\": \"anthropic:Message/stopReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"stop_sequence\": {\n          \"@id\": \"anthropic:Message/stopSequence\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"anthropic:Message/usage\",\n          \"@type\": \"anthropic:Usage\"\n        }\n      }\n    },\n\n    \"MessageRequest\": {\n      \"@id\": \"anthropic:MessageRequest\",\n      \"@context\": {\n        \"model\": {\n          \"@id\": \"anthropic:MessageRequest/model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"messages\": {\n          \"@id\": \"anthropic:MessageRequest/messages\",\n          \"@container\": \"@list\"\n        },\n        \"max_tokens\": {\n          \"@id\": \"anthropic:MessageRequest/maxTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"system\": {\n          \"@id\": \"anthropic:MessageRequest/system\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"temperature\": {\n          \"@id\": \"anthropic:MessageRequest/temperature\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"top_p\": {\n          \"@id\": \"anthropic:MessageRequest/topP\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"top_k\": {\n          \"@id\": \"anthropic:MessageRequest/topK\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"stop_sequences\": {\n          \"@id\": \"anthropic:MessageRequest/stopSequences\",\n          \"@container\": \"@list\"\n        },\n        \"stream\": {\n          \"@id\": \"anthropic:MessageRequest/stream\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"metadata\": {\n          \"@id\": \"anthropic:MessageRequest/metadata\",\n          \"@type\": \"anthropic:Metadata\"\n        },\n        \"tools\": {\n          \"@id\": \"anthropic:MessageRequest/tools\",\n          \"@container\": \"@list\"\n        },\n        \"tool_choice\"\
  : {\n          \"@id\": \"anthropic:MessageRequest/toolChoice\",\n          \"@type\": \"anthropic:ToolChoice\"\n        },\n        \"thinking\": {\n          \"@id\": \"anthropic:MessageRequest/thinking\",\n          \"@type\": \"anthropic:ThinkingConfig\"\n        },\n        \"service_tier\": {\n          \"@id\": \"anthropic:MessageRequest/serviceTier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MessageParam\": {\n      \"@id\": \"anthropic:MessageParam\",\n      \"@context\": {\n        \"role\": {\n          \"@id\": \"anthropic:MessageParam/role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"anthropic:MessageParam/content\"\n        }\n      }\n    },\n\n    \"TextBlock\": {\n      \"@id\": \"anthropic:TextBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:TextBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\":\
  \ \"anthropic:TextBlock/text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"citations\": {\n          \"@id\": \"anthropic:TextBlock/citations\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ImageBlock\": {\n      \"@id\": \"anthropic:ImageBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ImageBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"anthropic:ImageBlock/source\",\n          \"@type\": \"anthropic:ImageSource\"\n        }\n      }\n    },\n\n    \"DocumentBlock\": {\n      \"@id\": \"anthropic:DocumentBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:DocumentBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"anthropic:DocumentBlock/source\",\n          \"@type\": \"anthropic:DocumentSource\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": {\n          \"@id\": \"anthropic:DocumentBlock/context\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ToolDefinition\": {\n      \"@id\": \"anthropic:ToolDefinition\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"input_schema\": {\n          \"@id\": \"anthropic:ToolDefinition/inputSchema\",\n          \"@type\": \"anthropic:ToolInputSchema\"\n        }\n      }\n    },\n\n    \"ToolUseBlock\": {\n      \"@id\": \"anthropic:ToolUseBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ToolUseBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"anthropic:ToolUseBlock/id\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"anthropic:ToolUseBlock/name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"input\": {\n          \"@id\": \"anthropic:ToolUseBlock/input\"\n        }\n      }\n    },\n\n    \"ToolResultBlock\": {\n      \"@id\": \"anthropic:ToolResultBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ToolResultBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tool_use_id\": {\n          \"@id\": \"anthropic:ToolResultBlock/toolUseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"anthropic:ToolResultBlock/content\"\n        },\n        \"is_error\": {\n          \"@id\": \"anthropic:ToolResultBlock/isError\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ToolChoice\": {\n      \"@id\": \"anthropic:ToolChoice\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ToolChoice/type\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"anthropic:ToolChoice/name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disable_parallel_tool_use\": {\n          \"@id\": \"anthropic:ToolChoice/disableParallelToolUse\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ThinkingBlock\": {\n      \"@id\": \"anthropic:ThinkingBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ThinkingBlock/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thinking\": {\n          \"@id\": \"anthropic:ThinkingBlock/thinking\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signature\": {\n          \"@id\": \"anthropic:ThinkingBlock/signature\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ThinkingConfig\": {\n      \"@id\": \"anthropic:ThinkingConfig\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ThinkingConfig/type\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"budget_tokens\": {\n          \"@id\": \"anthropic:ThinkingConfig/budgetTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"anthropic:Usage\",\n      \"@context\": {\n        \"input_tokens\": {\n          \"@id\": \"anthropic:Usage/inputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"output_tokens\": {\n          \"@id\": \"anthropic:Usage/outputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cache_creation_input_tokens\": {\n          \"@id\": \"anthropic:Usage/cacheCreationInputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cache_read_input_tokens\": {\n          \"@id\": \"anthropic:Usage/cacheReadInputTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Citation\": {\n      \"@id\": \"anthropic:Citation\",\n      \"@context\": {\n        \"type\": {\n       \
  \   \"@id\": \"anthropic:Citation/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cited_text\": {\n          \"@id\": \"anthropic:Citation/citedText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"document_index\": {\n          \"@id\": \"anthropic:Citation/documentIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"document_title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"file_id\": {\n          \"@id\": \"anthropic:Citation/fileId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_char_index\": {\n          \"@id\": \"anthropic:Citation/startCharIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"end_char_index\": {\n          \"@id\": \"anthropic:Citation/endCharIndex\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"CacheControl\": {\n      \"@id\": \"anthropic:CacheControl\",\n      \"@context\": {\n     \
  \   \"type\": {\n          \"@id\": \"anthropic:CacheControl/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ttl\": {\n          \"@id\": \"anthropic:CacheControl/ttl\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Metadata\": {\n      \"@id\": \"anthropic:Metadata\",\n      \"@context\": {\n        \"user_id\": {\n          \"@id\": \"anthropic:Metadata/userId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ErrorResponse\": {\n      \"@id\": \"anthropic:ErrorResponse\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:ErrorResponse/type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"error\": {\n          \"@id\": \"anthropic:ErrorResponse/error\",\n          \"@type\": \"anthropic:Error\"\n        }\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"anthropic:Error\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"anthropic:Error/type\",\n   \
  \       \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"anthropic:Error/message\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/anthropic/refs/heads/main/json-ld/anthropic-context.jsonld
tags:
- AI
- Artificial Intelligence
- Claude
- Foundation Models
- Large Language Models
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
