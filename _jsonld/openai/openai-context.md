---
api_specs:
- filename: assistants-openapi-original.yml
  format: yaml
  label: OpenAI Assistants API
  slug: openai-assistants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/assistants-openapi-original.yml
- filename: audio-openapi-original.yml
  format: yaml
  label: OpenAI Audio API
  slug: openai-audio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/audio-openapi-original.yml
- filename: chat-openapi-original.yml
  format: yaml
  label: OpenAI Chat API
  slug: openai-chat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/chat-openapi-original.yml
- filename: openai-chat-completions-openapi.yml
  format: yaml
  label: OpenAI Chat Completions API
  slug: openai-chat-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/openai-chat-completions-openapi.yml
- filename: embeddings-openapi-original.yml
  format: yaml
  label: OpenAI Embeddings API
  slug: openai-embeddings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/embeddings-openapi-original.yml
- filename: files-openapi-original.yml
  format: yaml
  label: OpenAI Files API
  slug: openai-files-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/files-openapi-original.yml
- filename: fine-tuning-openapi-original.yml
  format: yaml
  label: OpenAI Fine Tuning API
  slug: openai-fine-tuning-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/fine-tuning-openapi-original.yml
- filename: images-openapi-original.yml
  format: yaml
  label: OpenAI Images API
  slug: openai-images-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/images-openapi-original.yml
- filename: models-openapi-original.yml
  format: yaml
  label: OpenAI Models API
  slug: openai-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/models-openapi-original.yml
- filename: threads-openapi-original.yml
  format: yaml
  label: OpenAI Threads API
  slug: openai-threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/threads-openapi-original.yml
- filename: completions-openapi-original.yml
  format: yaml
  label: OpenAI Completions API
  slug: openai-completions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/openapi/completions-openapi-original.yml
class_count: 0
classes: []
context_file: json-ld/openai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/json-ld/openai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Openai from OpenAI.
layout: jsonld
name: Openai Context
namespaces:
- prefix: openai
  uri: https://platform.openai.com/docs/ns/
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
  name: Choice
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: ToolCall
  type: ''
- container: ''
  name: Function
  type: ''
- container: ''
  name: Usage
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: EmbeddingResponse
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: ImagesResponse
  type: ''
- container: ''
  name: Transcription
  type: ''
- container: ''
  name: Translation
  type: ''
- container: ''
  name: Speech
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 15
provider_name: OpenAI
provider_slug: openai
slug: openai-context
source_filename: openai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"openai\": \"https://platform.openai.com/docs/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatCompletion\": {\n      \"@id\": \"openai:ChatCompletion\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"object\": \"openai:objectType\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": \"openai:model\",\n        \"system_fingerprint\": \"openai:systemFingerprint\",\n        \"service_tier\": \"openai:serviceTier\",\n        \"choices\": {\n          \"@id\": \"openai:choices\",\n          \"@container\": \"@list\"\n        },\n        \"usage\": \"openai:usage\"\n      }\n    },\n\n    \"Choice\": {\n      \"@id\": \"openai:Choice\",\n      \"@context\": {\n        \"index\": \"openai:index\",\n        \"\
  message\": \"openai:message\",\n        \"finish_reason\": \"openai:finishReason\",\n        \"logprobs\": \"openai:logprobs\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"openai:Message\",\n      \"@context\": {\n        \"role\": \"openai:role\",\n        \"content\": \"schema:text\",\n        \"name\": \"schema:name\",\n        \"tool_calls\": {\n          \"@id\": \"openai:toolCalls\",\n          \"@container\": \"@list\"\n        },\n        \"tool_call_id\": \"openai:toolCallId\",\n        \"refusal\": \"openai:refusal\"\n      }\n    },\n\n    \"ToolCall\": {\n      \"@id\": \"openai:ToolCall\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"openai:toolType\",\n        \"function\": \"openai:function\"\n      }\n    },\n\n    \"Function\": {\n      \"@id\": \"openai:Function\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"parameters\": \"openai:parameters\"\
  ,\n        \"arguments\": \"openai:arguments\"\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"openai:Usage\",\n      \"@context\": {\n        \"prompt_tokens\": \"openai:promptTokens\",\n        \"completion_tokens\": \"openai:completionTokens\",\n        \"total_tokens\": \"openai:totalTokens\",\n        \"completion_tokens_details\": \"openai:completionTokensDetails\",\n        \"prompt_tokens_details\": \"openai:promptTokensDetails\"\n      }\n    },\n\n    \"Embedding\": {\n      \"@id\": \"openai:Embedding\",\n      \"@context\": {\n        \"object\": \"openai:objectType\",\n        \"embedding\": \"openai:embeddingVector\",\n        \"index\": \"openai:index\",\n        \"model\": \"openai:model\",\n        \"usage\": \"openai:usage\"\n      }\n    },\n\n    \"EmbeddingResponse\": {\n      \"@id\": \"openai:EmbeddingResponse\",\n      \"@context\": {\n        \"object\": \"openai:objectType\",\n        \"data\": {\n          \"@id\": \"openai:data\",\n          \"@container\"\
  : \"@list\"\n        },\n        \"model\": \"openai:model\",\n        \"usage\": \"openai:usage\"\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"openai:Image\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"b64_json\": \"openai:base64Json\",\n        \"revised_prompt\": \"openai:revisedPrompt\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ImagesResponse\": {\n      \"@id\": \"openai:ImagesResponse\",\n      \"@context\": {\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"data\": {\n          \"@id\": \"openai:data\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Transcription\": {\n      \"@id\": \"openai:Transcription\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n      \
  \  \"task\": \"openai:task\",\n        \"language\": \"schema:inLanguage\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:float\"\n        },\n        \"words\": {\n          \"@id\": \"openai:words\",\n          \"@container\": \"@list\"\n        },\n        \"segments\": {\n          \"@id\": \"openai:segments\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Translation\": {\n      \"@id\": \"openai:Translation\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"task\": \"openai:task\",\n        \"language\": \"schema:inLanguage\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:float\"\n        },\n        \"segments\": {\n          \"@id\": \"openai:segments\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Speech\": {\n      \"@id\": \"openai:Speech\",\n      \"@context\": {\n        \"model\": \"openai:model\",\n\
  \        \"voice\": \"openai:voice\",\n        \"input\": \"schema:text\",\n        \"response_format\": \"openai:responseFormat\",\n        \"speed\": \"openai:speed\"\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"openai:Model\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"object\": \"openai:objectType\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"owned_by\": \"schema:creator\"\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"openai:Error\",\n      \"@context\": {\n        \"message\": \"schema:description\",\n        \"type\": \"openai:errorType\",\n        \"param\": \"openai:errorParam\",\n        \"code\": \"openai:errorCode\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/openai/refs/heads/main/json-ld/openai-context.jsonld
tags:
- AI
- Artificial Intelligence
- Large Language Models
- T1
- JSON-LD
- Linked Data
- Semantic Web
---
