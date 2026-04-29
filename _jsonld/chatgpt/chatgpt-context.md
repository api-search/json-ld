---
class_count: 0
classes: []
context_file: json-ld/chatgpt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chatgpt/refs/heads/main/json-ld/chatgpt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chatgpt from ChatGPT.
layout: jsonld
name: Chatgpt Context
namespaces:
- prefix: openai
  uri: https://platform.openai.com/docs/api-reference/
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
  name: Response
  type: ''
- container: ''
  name: Choice
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: OutputItem
  type: ''
- container: ''
  name: OutputContentPart
  type: ''
- container: ''
  name: ContentPart
  type: ''
- container: ''
  name: ToolCall
  type: ''
- container: ''
  name: FunctionCall
  type: ''
- container: ''
  name: FunctionDefinition
  type: ''
- container: ''
  name: Tool
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: Usage
  type: ''
- container: ''
  name: ReasoningConfig
  type: ''
- container: ''
  name: ResponseFormat
  type: ''
- container: ''
  name: ImageUrl
  type: ''
property_count: 16
provider_name: ChatGPT
provider_slug: chatgpt
slug: chatgpt-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"openai\": \"https://platform.openai.com/docs/api-reference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatCompletion\": {\n      \"@id\": \"openai:ChatCompletion\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"object\": \"openai:objectType\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": \"openai:model\",\n        \"choices\": {\n          \"@id\": \"openai:choices\",\n          \"@container\": \"@list\"\n        },\n        \"usage\": \"openai:usage\",\n        \"system_fingerprint\": \"openai:systemFingerprint\",\n        \"service_tier\": \"openai:serviceTier\"\n      }\n    },\n\n    \"Response\": {\n      \"@id\": \"openai:Response\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"object\":\
  \ \"openai:objectType\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": \"openai:model\",\n        \"status\": \"openai:status\",\n        \"output\": {\n          \"@id\": \"openai:output\",\n          \"@container\": \"@list\"\n        },\n        \"usage\": \"openai:usage\",\n        \"instructions\": \"openai:instructions\",\n        \"metadata\": \"openai:metadata\",\n        \"temperature\": \"openai:temperature\",\n        \"top_p\": \"openai:topP\",\n        \"max_output_tokens\": \"openai:maxOutputTokens\",\n        \"previous_response_id\": \"openai:previousResponseId\",\n        \"reasoning\": \"openai:reasoning\",\n        \"tools\": {\n          \"@id\": \"openai:tools\",\n          \"@container\": \"@set\"\n        },\n        \"truncation\": \"openai:truncation\",\n        \"user\": \"openai:endUser\",\n        \"service_tier\": \"openai:serviceTier\"\n      }\n    },\n\n    \"Choice\"\
  : {\n      \"@id\": \"openai:Choice\",\n      \"@context\": {\n        \"index\": \"openai:index\",\n        \"message\": \"openai:message\",\n        \"finish_reason\": \"openai:finishReason\",\n        \"logprobs\": \"openai:logprobs\"\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"openai:Message\",\n      \"@context\": {\n        \"role\": \"openai:role\",\n        \"content\": \"openai:content\",\n        \"name\": \"schema:name\",\n        \"tool_calls\": {\n          \"@id\": \"openai:toolCalls\",\n          \"@container\": \"@list\"\n        },\n        \"tool_call_id\": \"openai:toolCallId\",\n        \"refusal\": \"openai:refusal\"\n      }\n    },\n\n    \"OutputItem\": {\n      \"@id\": \"openai:OutputItem\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": \"openai:outputItemType\",\n        \"role\": \"openai:role\",\n        \"status\": \"openai:status\",\n        \"content\": {\n          \"@id\": \"openai:content\",\n          \"@container\"\
  : \"@list\"\n        },\n        \"name\": \"schema:name\",\n        \"call_id\": \"openai:callId\",\n        \"arguments\": \"openai:arguments\",\n        \"summary\": {\n          \"@id\": \"openai:summary\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"OutputContentPart\": {\n      \"@id\": \"openai:OutputContentPart\",\n      \"@context\": {\n        \"type\": \"openai:contentPartType\",\n        \"text\": \"openai:text\",\n        \"refusal\": \"openai:refusal\",\n        \"annotations\": {\n          \"@id\": \"openai:annotations\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ContentPart\": {\n      \"@id\": \"openai:ContentPart\",\n      \"@context\": {\n        \"type\": \"openai:contentPartType\",\n        \"text\": \"openai:text\",\n        \"image_url\": \"openai:imageUrl\",\n        \"input_audio\": \"openai:inputAudio\"\n      }\n    },\n\n    \"ToolCall\": {\n      \"@id\": \"openai:ToolCall\",\n      \"@context\"\
  : {\n        \"id\": \"@id\",\n        \"type\": \"openai:toolCallType\",\n        \"function\": \"openai:function\"\n      }\n    },\n\n    \"FunctionCall\": {\n      \"@id\": \"openai:FunctionCall\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"arguments\": \"openai:arguments\"\n      }\n    },\n\n    \"FunctionDefinition\": {\n      \"@id\": \"openai:FunctionDefinition\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"parameters\": \"openai:parameters\",\n        \"strict\": \"openai:strict\"\n      }\n    },\n\n    \"Tool\": {\n      \"@id\": \"openai:Tool\",\n      \"@context\": {\n        \"type\": \"openai:toolType\",\n        \"name\": \"schema:name\",\n        \"description\": \"dcterms:description\",\n        \"parameters\": \"openai:parameters\",\n        \"strict\": \"openai:strict\",\n        \"vector_store_ids\": {\n          \"@id\": \"openai:vectorStoreIds\",\n          \"\
  @container\": \"@set\"\n        },\n        \"max_num_results\": \"openai:maxNumResults\",\n        \"server_label\": \"openai:serverLabel\",\n        \"server_url\": {\n          \"@id\": \"openai:serverUrl\",\n          \"@type\": \"@id\"\n        },\n        \"allowed_tools\": {\n          \"@id\": \"openai:allowedTools\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Annotation\": {\n      \"@id\": \"openai:Annotation\",\n      \"@context\": {\n        \"type\": \"openai:annotationType\",\n        \"start_index\": \"openai:startIndex\",\n        \"end_index\": \"openai:endIndex\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"title\": \"schema:name\",\n        \"file_id\": \"openai:fileId\",\n        \"quote\": \"openai:quote\"\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"openai:Usage\",\n      \"@context\": {\n        \"prompt_tokens\": \"openai:promptTokens\",\n        \"completion_tokens\"\
  : \"openai:completionTokens\",\n        \"total_tokens\": \"openai:totalTokens\",\n        \"input_tokens\": \"openai:inputTokens\",\n        \"output_tokens\": \"openai:outputTokens\",\n        \"completion_tokens_details\": \"openai:completionTokensDetails\",\n        \"prompt_tokens_details\": \"openai:promptTokensDetails\",\n        \"input_tokens_details\": \"openai:inputTokensDetails\",\n        \"output_tokens_details\": \"openai:outputTokensDetails\"\n      }\n    },\n\n    \"ReasoningConfig\": {\n      \"@id\": \"openai:ReasoningConfig\",\n      \"@context\": {\n        \"effort\": \"openai:effort\",\n        \"summary\": \"openai:reasoningSummary\"\n      }\n    },\n\n    \"ResponseFormat\": {\n      \"@id\": \"openai:ResponseFormat\",\n      \"@context\": {\n        \"type\": \"openai:formatType\",\n        \"json_schema\": \"openai:jsonSchema\"\n      }\n    },\n\n    \"ImageUrl\": {\n      \"@id\": \"openai:ImageUrl\",\n      \"@context\": {\n        \"url\": {\n         \
  \ \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"detail\": \"openai:detail\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chatgpt/refs/heads/main/json-ld/chatgpt-context.jsonld
tags:
- Agents
- AI
- ChatGPT
- Embeddings
- Fine-Tuning
- GPT-4
- GPT-5
- Language Model
- OpenAI
- Realtime
- JSON-LD
- Linked Data
- Semantic Web
---
