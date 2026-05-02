---
api_specs:
- filename: mistral-ai-chat-completions-openapi.yml
  format: yaml
  label: Mistral AI Chat Completions API
  slug: chat-completions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-chat-completions-openapi.yml
- filename: mistral-ai-embeddings-openapi.yml
  format: yaml
  label: Mistral AI Embeddings API
  slug: embeddings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-embeddings-openapi.yml
- filename: mistral-ai-agents-openapi.yml
  format: yaml
  label: Mistral AI Agents API
  slug: agents
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-agents-openapi.yml
- filename: mistral-ai-fine-tuning-openapi.yml
  format: yaml
  label: Mistral AI Fine-Tuning API
  slug: fine-tuning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-fine-tuning-openapi.yml
- filename: mistral-ai-ocr-openapi.yml
  format: yaml
  label: Mistral AI OCR API
  slug: ocr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-ocr-openapi.yml
- filename: mistral-ai-models-openapi.yml
  format: yaml
  label: Mistral AI Models API
  slug: models
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-models-openapi.yml
- filename: mistral-ai-forge-openapi.yml
  format: yaml
  label: Mistral AI Forge API
  slug: forge
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-forge-openapi.yml
- filename: mistral-ai-batch-openapi.yml
  format: yaml
  label: Mistral AI Batch API
  slug: batch
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/openapi/mistral-ai-batch-openapi.yml
class_count: 0
classes: []
context_file: json-ld/mistral-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/json-ld/mistral-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mistral Ai from Mistral AI.
layout: jsonld
name: Mistral Ai Context
namespaces:
- prefix: mistral
  uri: https://api.mistral.ai/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: ml
  uri: http://www.w3.org/ns/mls#
properties:
- container: ''
  name: Model
  type: ''
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: ChatMessage
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: FineTuningJob
  type: ''
- container: ''
  name: BatchJob
  type: ''
- container: ''
  name: OcrResult
  type: ''
- container: ''
  name: Agent
  type: ''
property_count: 8
provider_name: Mistral AI
provider_slug: mistral-ai
slug: mistral-ai-context
source_filename: mistral-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mistral\": \"https://api.mistral.ai/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"ml\": \"http://www.w3.org/ns/mls#\",\n\n    \"Model\": {\n      \"@id\": \"mistral:Model\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"owned_by\": \"schema:provider\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"max_context_length\": {\n          \"@id\": \"mistral:maxContextLength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"aliases\": {\n          \"@id\": \"schema:alternateName\",\n          \"@container\": \"@set\"\n        },\n        \"deprecation\": {\n          \"@id\": \"mistral:deprecation\",\n          \"\
  @type\": \"xsd:dateTime\"\n        },\n        \"capabilities\": \"mistral:capabilities\",\n        \"type\": \"mistral:modelType\"\n      }\n    },\n\n    \"ChatCompletion\": {\n      \"@id\": \"mistral:ChatCompletion\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"model\": {\n          \"@id\": \"mistral:usesModel\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"choices\": {\n          \"@id\": \"mistral:choices\",\n          \"@container\": \"@list\"\n        },\n        \"usage\": \"mistral:tokenUsage\"\n      }\n    },\n\n    \"ChatMessage\": {\n      \"@id\": \"mistral:ChatMessage\",\n      \"@context\": {\n        \"role\": \"mistral:role\",\n        \"content\": \"schema:text\",\n        \"tool_calls\": {\n          \"@id\": \"mistral:toolCalls\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Embedding\"\
  : {\n      \"@id\": \"mistral:Embedding\",\n      \"@context\": {\n        \"model\": {\n          \"@id\": \"mistral:usesModel\",\n          \"@type\": \"@id\"\n        },\n        \"embedding\": {\n          \"@id\": \"mistral:vector\",\n          \"@container\": \"@list\"\n        },\n        \"index\": {\n          \"@id\": \"mistral:index\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"FineTuningJob\": {\n      \"@id\": \"mistral:FineTuningJob\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"model\": {\n          \"@id\": \"mistral:baseModel\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"mistral:jobStatus\",\n        \"fine_tuned_model\": {\n          \"@id\": \"mistral:outputModel\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"modified_at\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"training_files\": {\n          \"@id\": \"mistral:trainingFiles\",\n          \"@container\": \"@set\"\n        },\n        \"hyperparameters\": \"ml:hasHyperParameter\"\n      }\n    },\n\n    \"BatchJob\": {\n      \"@id\": \"mistral:BatchJob\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"model\": {\n          \"@id\": \"mistral:usesModel\",\n          \"@type\": \"@id\"\n        },\n        \"endpoint\": {\n          \"@id\": \"mistral:targetEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"mistral:jobStatus\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_requests\": {\n          \"@id\": \"mistral:totalRequests\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completed_requests\": {\n          \"@id\": \"mistral:completedRequests\",\n          \"@type\": \"xsd:integer\"\
  \n        }\n      }\n    },\n\n    \"OcrResult\": {\n      \"@id\": \"mistral:OcrResult\",\n      \"@context\": {\n        \"pages\": {\n          \"@id\": \"mistral:pages\",\n          \"@container\": \"@list\"\n        },\n        \"model\": {\n          \"@id\": \"mistral:usesModel\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"mistral:Agent\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"model\": {\n          \"@id\": \"mistral:usesModel\",\n          \"@type\": \"@id\"\n        },\n        \"instructions\": \"mistral:instructions\",\n        \"tools\": {\n          \"@id\": \"mistral:tools\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mistral-ai/refs/heads/main/json-ld/mistral-ai-context.jsonld
tags:
- Agents
- Artificial Intelligence
- Batch Processing
- Chat
- Embeddings
- Fine-Tuning
- Large Language Models
- OCR
- JSON-LD
- Linked Data
- Semantic Web
---
