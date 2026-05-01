---
api_specs:
- filename: deepseek-chat-completion-api-openapi.yml
  format: yaml
  label: DeepSeek Chat Completion API
  slug: deepseek-chat-completion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-chat-completion-api-openapi.yml
- filename: deepseek-fim-completion-openapi.yml
  format: yaml
  label: DeepSeek Fill-In-The-Middle (FIM) Completion API
  slug: deepseek-fim-completion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-fim-completion-openapi.yml
- filename: deepseek-lists-models-api-openapi.yml
  format: yaml
  label: DeepSeek List Models API
  slug: deepseek-lists-models-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-lists-models-api-openapi.yml
- filename: deepseek-user-balance-api-openapi.yml
  format: yaml
  label: DeepSeek User Balance API
  slug: deepseek-user-balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/openapi/deepseek-user-balance-api-openapi.yml
class_count: 6
classes:
- ChatCompletion
- Message
- Model
- ToolCall
- Usage
- Balance
context_file: json-ld/deepseek-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/json-ld/deepseek-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Deepseek from DeepSeek.
layout: jsonld
name: Deepseek Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: deepseek
  uri: https://schema.deepseek.com/
properties:
- container: ''
  name: id
  type: schema:Text
- container: ''
  name: model
  type: schema:Text
- container: ''
  name: role
  type: schema:Text
- container: ''
  name: content
  type: schema:Text
- container: ''
  name: prompt_tokens
  type: schema:Integer
- container: ''
  name: completion_tokens
  type: schema:Integer
- container: ''
  name: total_tokens
  type: schema:Integer
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: total_balance
  type: schema:Number
property_count: 9
provider_name: DeepSeek
provider_slug: deepseek
slug: deepseek-context
source_filename: deepseek-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.deepseek.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"deepseek\": \"https://schema.deepseek.com/\",\n    \"ChatCompletion\": \"deepseek:ChatCompletion\",\n    \"Message\": \"deepseek:Message\",\n    \"Model\": \"deepseek:Model\",\n    \"ToolCall\": \"deepseek:ToolCall\",\n    \"Usage\": \"deepseek:Usage\",\n    \"Balance\": \"deepseek:Balance\",\n    \"id\": {\"@id\": \"schema:identifier\", \"@type\": \"schema:Text\"},\n    \"model\": {\"@id\": \"deepseek:model\", \"@type\": \"schema:Text\"},\n    \"role\": {\"@id\": \"deepseek:role\", \"@type\": \"schema:Text\"},\n    \"content\": {\"@id\": \"schema:text\", \"@type\": \"schema:Text\"},\n    \"prompt_tokens\": {\"@id\": \"deepseek:promptTokens\", \"@type\": \"schema:Integer\"},\n    \"completion_tokens\": {\"@id\": \"deepseek:completionTokens\", \"@type\": \"schema:Integer\"},\n    \"total_tokens\": {\"@id\": \"deepseek:totalTokens\"\
  , \"@type\": \"schema:Integer\"},\n    \"currency\": {\"@id\": \"schema:priceCurrency\", \"@type\": \"schema:Text\"},\n    \"total_balance\": {\"@id\": \"deepseek:totalBalance\", \"@type\": \"schema:Number\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/json-ld/deepseek-context.jsonld
tags:
- AI
- Artificial Intelligence
- Chat
- Chat Completion
- LLM
- Large Language Models
- Reasoning
- Code Completion
- JSON-LD
- Linked Data
- Semantic Web
---
