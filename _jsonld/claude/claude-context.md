---
api_specs:
- filename: claude-messages-api.yml
  format: yaml
  label: Claude Messages API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/claude/refs/heads/main/openapi/claude-messages-api.yml
class_count: 0
classes: []
context_file: json-ld/claude-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/claude/refs/heads/main/json-ld/claude-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Claude from Claude.
layout: jsonld
name: Claude Context
namespaces:
- prefix: anthropic
  uri: https://api.anthropic.com/v1/
- prefix: claude
  uri: https://api.anthropic.com/v1/schemas/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: CreateMessageRequest
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
  name: ImageSource
  type: ''
- container: ''
  name: DocumentBlock
  type: ''
- container: ''
  name: ToolUseBlock
  type: ''
- container: ''
  name: ToolResultBlock
  type: ''
- container: ''
  name: ThinkingBlock
  type: ''
- container: ''
  name: ToolDefinition
  type: ''
- container: ''
  name: ToolChoice
  type: ''
- container: ''
  name: Usage
  type: ''
- container: ''
  name: Metadata
  type: ''
- container: ''
  name: ThinkingConfig
  type: ''
- container: ''
  name: CacheControl
  type: ''
- container: ''
  name: ModelInfo
  type: ''
- container: ''
  name: MessageBatch
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 20
provider_name: Claude
provider_slug: claude
slug: claude-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"anthropic\": \"https://api.anthropic.com/v1/\",\n    \"claude\": \"https://api.anthropic.com/v1/schemas/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Message\": {\n      \"@id\": \"claude:Message\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"claude:messageId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"claude:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"claude:role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"claude:content\",\n          \"@container\": \"@list\"\n        },\n        \"model\": {\n          \"@id\": \"claude:model\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"stop_reason\": {\n          \"@id\": \"claude:stopReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"stop_sequence\": {\n          \"@id\": \"claude:stopSequence\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"claude:usage\",\n          \"@type\": \"claude:Usage\"\n        }\n      }\n    },\n\n    \"CreateMessageRequest\": {\n      \"@id\": \"claude:CreateMessageRequest\",\n      \"@context\": {\n        \"model\": {\n          \"@id\": \"claude:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"max_tokens\": {\n          \"@id\": \"claude:maxTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"messages\": {\n          \"@id\": \"claude:messages\",\n          \"@container\": \"@list\"\n        },\n        \"system\": {\n          \"@id\": \"claude:systemPrompt\"\n        },\n        \"temperature\": {\n          \"@id\": \"claude:temperature\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"top_p\": {\n          \"@id\": \"claude:topP\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"top_k\": {\n          \"@id\": \"claude:topK\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"stop_sequences\": {\n          \"@id\": \"claude:stopSequences\",\n          \"@container\": \"@list\"\n        },\n        \"stream\": {\n          \"@id\": \"claude:stream\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"metadata\": {\n          \"@id\": \"claude:metadata\",\n          \"@type\": \"claude:Metadata\"\n        },\n        \"tools\": {\n          \"@id\": \"claude:tools\",\n          \"@container\": \"@list\"\n        },\n        \"tool_choice\": {\n          \"@id\": \"claude:toolChoice\",\n          \"@type\": \"claude:ToolChoice\"\n        },\n        \"thinking\": {\n          \"@id\": \"claude:thinking\",\n          \"@type\": \"claude:ThinkingConfig\"\n        },\n        \"service_tier\": {\n          \"@id\":\
  \ \"claude:serviceTier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MessageParam\": {\n      \"@id\": \"claude:MessageParam\",\n      \"@context\": {\n        \"role\": {\n          \"@id\": \"claude:role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"claude:content\"\n        }\n      }\n    },\n\n    \"TextBlock\": {\n      \"@id\": \"claude:TextBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\": \"claude:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"citations\": {\n          \"@id\": \"claude:citations\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ImageBlock\": {\n      \"@id\": \"claude:ImageBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"source\": {\n          \"@id\": \"claude:imageSource\",\n          \"@type\": \"claude:ImageSource\"\n        }\n      }\n    },\n\n    \"ImageSource\": {\n      \"@id\": \"claude:ImageSource\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:sourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"media_type\": {\n          \"@id\": \"claude:mediaType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": {\n          \"@id\": \"claude:base64Data\",\n          \"@type\": \"xsd:base64Binary\"\n        },\n        \"url\": {\n          \"@id\": \"claude:sourceUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"DocumentBlock\": {\n      \"@id\": \"claude:DocumentBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"claude:documentSource\",\n          \"\
  @type\": \"claude:DocumentSource\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": {\n          \"@id\": \"claude:documentContext\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ToolUseBlock\": {\n      \"@id\": \"claude:ToolUseBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"claude:toolUseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"claude:toolName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"input\": {\n          \"@id\": \"claude:toolInput\"\n        }\n      }\n    },\n\n    \"ToolResultBlock\": {\n      \"@id\": \"claude:ToolResultBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"tool_use_id\": {\n          \"@id\": \"claude:toolUseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"claude:toolResultContent\"\n        },\n        \"is_error\": {\n          \"@id\": \"claude:isError\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ThinkingBlock\": {\n      \"@id\": \"claude:ThinkingBlock\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:blockType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thinking\": {\n          \"@id\": \"claude:thinkingText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signature\": {\n          \"@id\": \"claude:thinkingSignature\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ToolDefinition\": {\n      \"@id\": \"claude:ToolDefinition\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"claude:toolName\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"input_schema\": {\n          \"@id\": \"claude:inputSchema\"\n        },\n        \"type\": {\n          \"@id\": \"claude:toolType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ToolChoice\": {\n      \"@id\": \"claude:ToolChoice\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:choiceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"claude:toolName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disable_parallel_tool_use\": {\n          \"@id\": \"claude:disableParallelToolUse\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"claude:Usage\",\n      \"@context\": {\n        \"input_tokens\": {\n          \"@id\": \"claude:inputTokens\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"output_tokens\": {\n          \"@id\": \"claude:outputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cache_creation_input_tokens\": {\n          \"@id\": \"claude:cacheCreationInputTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cache_read_input_tokens\": {\n          \"@id\": \"claude:cacheReadInputTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Metadata\": {\n      \"@id\": \"claude:Metadata\",\n      \"@context\": {\n        \"user_id\": {\n          \"@id\": \"claude:userId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ThinkingConfig\": {\n      \"@id\": \"claude:ThinkingConfig\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:thinkingType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"budget_tokens\": {\n          \"@id\": \"claude:budgetTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n     \
  \ }\n    },\n\n    \"CacheControl\": {\n      \"@id\": \"claude:CacheControl\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:cacheType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ttl\": {\n          \"@id\": \"claude:ttl\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ModelInfo\": {\n      \"@id\": \"claude:ModelInfo\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"claude:modelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"claude:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"display_name\": {\n          \"@id\": \"claude:displayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MessageBatch\": {\n      \"@id\": \"claude:MessageBatch\",\n      \"@context\": {\n        \"\
  id\": {\n          \"@id\": \"claude:batchId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"claude:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processing_status\": {\n          \"@id\": \"claude:processingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"request_counts\": {\n          \"@id\": \"claude:requestCounts\",\n          \"@type\": \"claude:RequestCounts\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ended_at\": {\n          \"@id\": \"claude:endedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expires_at\": {\n          \"@id\": \"claude:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"results_url\": {\n          \"@id\": \"claude:resultsUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"\
  claude:Error\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"error\": {\n          \"@id\": \"claude:errorDetail\",\n          \"@type\": \"claude:ErrorDetail\"\n        }\n      }\n    },\n\n    \"ErrorDetail\": {\n      \"@id\": \"claude:ErrorDetail\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"claude:errorType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"claude:errorMessage\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/claude/refs/heads/main/json-ld/claude-context.jsonld
tags:
- Artificial Intelligence
- Chatbot
- Conversational AI
- Generative AI
- Large Language Models
- Machine Learning
- Natural Language Processing
- JSON-LD
- Linked Data
- Semantic Web
---
