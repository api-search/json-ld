---
api_specs:
- filename: openapi.json
  format: json
  label: Mistral AI Chat API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.mistral.ai/openapi.json
- filename: mistral-embeddings-openapi.yml
  format: yaml
  label: Mistral Embeddings API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-embeddings-openapi.yml
- filename: mistral-moderation-openapi.yml
  format: yaml
  label: Mistral Moderation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-moderation-openapi.yml
- filename: mistral-agents-openapi.yml
  format: yaml
  label: Mistral AI Agents API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-agents-openapi.yml
- filename: mistral-fim-openapi.yml
  format: yaml
  label: Mistral AI FIM API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-fim-openapi.yml
- filename: mistral-ocr-openapi.yml
  format: yaml
  label: Mistral AI OCR API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-ocr-openapi.yml
- filename: mistral-fine-tuning-openapi.yml
  format: yaml
  label: Mistral AI Fine-Tuning API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-fine-tuning-openapi.yml
- filename: mistral-files-openapi.yml
  format: yaml
  label: Mistral AI Files API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-files-openapi.yml
- filename: mistral-models-openapi.yml
  format: yaml
  label: Mistral AI Models API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-models-openapi.yml
- filename: mistral-batch-openapi.yml
  format: yaml
  label: Mistral AI Batch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-batch-openapi.yml
- filename: mistral-audio-transcription-openapi.yml
  format: yaml
  label: Mistral AI Audio Transcription API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/openapi/mistral-audio-transcription-openapi.yml
class_count: 0
classes: []
context_file: json-ld/mistral-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/json-ld/mistral-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mistral from Mistral AI.
layout: jsonld
name: Mistral Context
namespaces:
- prefix: mistral
  uri: https://docs.mistral.ai/schemas/
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
  name: Message
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: FineTuningJob
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: ModerationResult
  type: ''
- container: ''
  name: BatchJob
  type: ''
- container: ''
  name: Transcription
  type: ''
- container: ''
  name: OcrResult
  type: ''
- container: ''
  name: Usage
  type: ''
property_count: 11
provider_name: Mistral AI
provider_slug: mistral
slug: mistral-context
source_filename: mistral-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mistral\": \"https://docs.mistral.ai/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatCompletion\": {\n      \"@id\": \"mistral:ChatCompletion\",\n      \"@context\": {\n        \"model\": \"mistral:model\",\n        \"choices\": \"mistral:choices\",\n        \"usage\": \"mistral:usage\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"mistral:Message\",\n      \"@context\": {\n        \"role\": \"mistral:role\",\n        \"content\": \"schema:text\",\n        \"toolCalls\": \"mistral:toolCalls\",\n        \"toolCallId\": \"mistral:toolCallId\"\n      }\n    },\n\n    \"Embedding\": {\n      \"@id\": \"mistral:Embedding\",\n      \"@context\": {\n        \"embedding\": \"mistral:embeddingVector\"\
  ,\n        \"index\": {\n          \"@id\": \"mistral:index\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": \"mistral:model\"\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"mistral:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"ownedBy\": \"mistral:ownedBy\",\n        \"maxContextLength\": {\n          \"@id\": \"mistral:maxContextLength\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"aliases\": \"mistral:aliases\",\n        \"capabilities\": \"mistral:capabilities\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"deprecation\": {\n          \"@id\": \"mistral:deprecation\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"FineTuningJob\": {\n      \"@id\": \"mistral:FineTuningJob\",\n      \"@context\": {\n        \"model\": \"mistral:model\",\n      \
  \  \"status\": \"mistral:status\",\n        \"jobType\": \"mistral:jobType\",\n        \"fineTunedModel\": \"mistral:fineTunedModel\",\n        \"trainingFiles\": \"mistral:trainingFiles\",\n        \"validationFiles\": \"mistral:validationFiles\",\n        \"hyperparameters\": \"mistral:hyperparameters\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"File\": {\n      \"@id\": \"mistral:File\",\n      \"@context\": {\n        \"filename\": \"schema:name\",\n        \"purpose\": \"mistral:purpose\",\n        \"bytes\": {\n          \"@id\": \"mistral:bytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numLines\": {\n          \"@id\": \"mistral:numLines\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"source\": \"mistral:source\",\n        \"\
  createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ModerationResult\": {\n      \"@id\": \"mistral:ModerationResult\",\n      \"@context\": {\n        \"categories\": \"mistral:categories\",\n        \"categoryScores\": \"mistral:categoryScores\",\n        \"model\": \"mistral:model\"\n      }\n    },\n\n    \"BatchJob\": {\n      \"@id\": \"mistral:BatchJob\",\n      \"@context\": {\n        \"endpoint\": \"mistral:endpoint\",\n        \"model\": \"mistral:model\",\n        \"status\": \"mistral:status\",\n        \"inputFiles\": \"mistral:inputFiles\",\n        \"outputFile\": \"mistral:outputFile\",\n        \"totalRequests\": {\n          \"@id\": \"mistral:totalRequests\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completedRequests\": {\n          \"@id\": \"mistral:completedRequests\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"\
  dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completedAt\": {\n          \"@id\": \"mistral:completedAt\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Transcription\": {\n      \"@id\": \"mistral:Transcription\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"language\": \"schema:inLanguage\",\n        \"duration\": {\n          \"@id\": \"mistral:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"words\": \"mistral:words\",\n        \"segments\": \"mistral:segments\"\n      }\n    },\n\n    \"OcrResult\": {\n      \"@id\": \"mistral:OcrResult\",\n      \"@context\": {\n        \"pages\": \"mistral:pages\",\n        \"model\": \"mistral:model\",\n        \"markdown\": \"schema:text\",\n        \"index\": {\n          \"@id\": \"mistral:index\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Usage\": {\n      \"@id\": \"mistral:Usage\",\n      \"@context\"\
  : {\n        \"promptTokens\": {\n          \"@id\": \"mistral:promptTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completionTokens\": {\n          \"@id\": \"mistral:completionTokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalTokens\": {\n          \"@id\": \"mistral:totalTokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mistral/refs/heads/main/json-ld/mistral-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
