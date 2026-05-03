---
api_specs:
- filename: openai-chat-completions-openapi.yml
  format: yaml
  label: OpenAI Chat Completions API
  slug: openai-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-chat-completions-openapi.yml
- filename: openai-completions-openapi.yml
  format: yaml
  label: OpenAI Completions API
  slug: openai-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-completions-openapi.yml
- filename: openai-images-openapi.yml
  format: yaml
  label: OpenAI Images API
  slug: openai-images-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-images-openapi.yml
- filename: openai-embeddings-openapi.yml
  format: yaml
  label: OpenAI Embeddings API
  slug: openai-embeddings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-embeddings-openapi.yml
- filename: openai-audio-openapi.yml
  format: yaml
  label: OpenAI Audio API
  slug: openai-audio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-audio-openapi.yml
- filename: openai-moderations-openapi.yml
  format: yaml
  label: OpenAI Moderations API
  slug: openai-moderations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-moderations-openapi.yml
- filename: openai-assistants-openapi.yml
  format: yaml
  label: OpenAI Assistants API
  slug: openai-assistants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/openapi/openai-assistants-openapi.yml
class_count: 0
classes: []
context_file: json-ld/openai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/json-ld/openai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openai from OpenAI APIs.
layout: jsonld
name: Openai Context
namespaces:
- prefix: openai
  uri: https://api.openai.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: ChatMessage
  type: ''
- container: ''
  name: Completion
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: Transcription
  type: ''
- container: ''
  name: Speech
  type: ''
- container: ''
  name: ModerationResult
  type: ''
- container: ''
  name: Assistant
  type: ''
- container: ''
  name: Thread
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Run
  type: ''
- container: ''
  name: Usage
  type: ''
property_count: 13
provider_name: OpenAI APIs
provider_slug: openai-apis
slug: openai-context
source_filename: openai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"openai\": \"https://api.openai.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatCompletion\": {\n      \"@id\": \"openai:ChatCompletion\",\n      \"@context\": {\n        \"model\": \"openai:model\",\n        \"choices\": \"openai:choices\",\n        \"usage\": \"openai:usage\",\n        \"systemFingerprint\": \"openai:systemFingerprint\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ChatMessage\": {\n      \"@id\": \"openai:ChatMessage\",\n      \"@context\": {\n        \"role\": \"openai:role\",\n        \"content\": \"schema:text\",\n        \"name\": \"schema:name\",\n        \"toolCalls\": \"openai:toolCalls\",\n        \"toolCallId\": \"openai:toolCallId\"\n      }\n    },\n\n    \"Completion\": {\n  \
  \    \"@id\": \"openai:Completion\",\n      \"@context\": {\n        \"model\": \"openai:model\",\n        \"choices\": \"openai:choices\",\n        \"usage\": \"openai:usage\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"openai:Image\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"b64Json\": \"openai:b64Json\",\n        \"revisedPrompt\": \"openai:revisedPrompt\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Embedding\": {\n      \"@id\": \"openai:Embedding\",\n      \"@context\": {\n        \"embedding\": \"openai:embeddingVector\",\n        \"index\": {\n          \"@id\": \"openai:index\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": \"openai:model\"\n   \
  \   }\n    },\n\n    \"Transcription\": {\n      \"@id\": \"openai:Transcription\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"language\": \"schema:inLanguage\",\n        \"duration\": {\n          \"@id\": \"openai:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"words\": \"openai:words\",\n        \"segments\": \"openai:segments\"\n      }\n    },\n\n    \"Speech\": {\n      \"@id\": \"openai:Speech\",\n      \"@context\": {\n        \"model\": \"openai:model\",\n        \"voice\": \"openai:voice\",\n        \"input\": \"schema:text\",\n        \"responseFormat\": \"openai:responseFormat\",\n        \"speed\": {\n          \"@id\": \"openai:speed\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ModerationResult\": {\n      \"@id\": \"openai:ModerationResult\",\n      \"@context\": {\n        \"flagged\": {\n          \"@id\": \"openai:flagged\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"\
  categories\": \"openai:categories\",\n        \"categoryScores\": \"openai:categoryScores\"\n      }\n    },\n\n    \"Assistant\": {\n      \"@id\": \"openai:Assistant\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"model\": \"openai:model\",\n        \"instructions\": \"openai:instructions\",\n        \"tools\": \"openai:tools\",\n        \"metadata\": \"openai:metadata\",\n        \"temperature\": {\n          \"@id\": \"openai:temperature\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Thread\": {\n      \"@id\": \"openai:Thread\",\n      \"@context\": {\n        \"metadata\": \"openai:metadata\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\"\
  : \"openai:Message\",\n      \"@context\": {\n        \"role\": \"openai:role\",\n        \"content\": \"schema:text\",\n        \"threadId\": \"openai:threadId\",\n        \"assistantId\": \"openai:assistantId\",\n        \"runId\": \"openai:runId\",\n        \"metadata\": \"openai:metadata\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Run\": {\n      \"@id\": \"openai:Run\",\n      \"@context\": {\n        \"status\": \"openai:runStatus\",\n        \"model\": \"openai:model\",\n        \"instructions\": \"openai:instructions\",\n        \"tools\": \"openai:tools\",\n        \"threadId\": \"openai:threadId\",\n        \"assistantId\": \"openai:assistantId\",\n        \"usage\": \"openai:usage\",\n        \"startedAt\": {\n          \"@id\": \"openai:startedAt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completedAt\": {\n          \"@id\": \"openai:completedAt\",\n   \
  \       \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"openai:Usage\",\n      \"@context\": {\n        \"promptTokens\": {\n          \"@id\": \"openai:promptTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completionTokens\": {\n          \"@id\": \"openai:completionTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalTokens\": {\n          \"@id\": \"openai:totalTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openai-apis/refs/heads/main/json-ld/openai-context.jsonld
tags:
- Artificial Intelligence
- Embeddings
- Image Generation
- Language Models
- Speech
- JSON-LD
- Linked Data
- Semantic Web
---
