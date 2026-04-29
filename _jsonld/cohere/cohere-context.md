---
class_count: 0
classes: []
context_file: json-ld/cohere-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/json-ld/cohere-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cohere from cohere.
layout: jsonld
name: Cohere Context
namespaces:
- prefix: cohere
  uri: https://api.cohere.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ChatMessage
  type: ''
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: RerankResult
  type: ''
- container: ''
  name: Classification
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: EmbedJob
  type: ''
- container: ''
  name: Tool
  type: ''
- container: ''
  name: ToolCall
  type: ''
property_count: 10
provider_name: cohere
provider_slug: cohere
slug: cohere-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cohere\": \"https://api.cohere.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ChatMessage\": {\n      \"@id\": \"cohere:ChatMessage\",\n      \"@context\": {\n        \"role\": \"cohere:role\",\n        \"content\": \"schema:text\",\n        \"toolCallId\": \"cohere:toolCallId\",\n        \"toolCalls\": {\n          \"@id\": \"cohere:toolCalls\",\n          \"@container\": \"@set\"\n        },\n        \"citations\": {\n          \"@id\": \"cohere:citations\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ChatCompletion\": {\n      \"@id\": \"cohere:ChatCompletion\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"finishReason\": \"cohere:finishReason\",\n        \"message\": \"cohere:message\",\n        \"usage\": \"cohere:usage\"\n      }\n    },\n\
  \n    \"Embedding\": {\n      \"@id\": \"cohere:Embedding\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"inputType\": \"cohere:inputType\",\n        \"embeddingType\": \"cohere:embeddingType\",\n        \"vectors\": {\n          \"@id\": \"cohere:vectors\",\n          \"@container\": \"@set\"\n        },\n        \"texts\": {\n          \"@id\": \"cohere:texts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"RerankResult\": {\n      \"@id\": \"cohere:RerankResult\",\n      \"@context\": {\n        \"index\": \"cohere:index\",\n        \"relevanceScore\": \"cohere:relevanceScore\",\n        \"document\": \"cohere:document\"\n      }\n    },\n\n    \"Classification\": {\n      \"@id\": \"cohere:Classification\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"input\": \"schema:text\",\n        \"prediction\": \"cohere:prediction\",\n        \"confidence\": \"cohere:confidence\",\n        \"\
  labels\": {\n          \"@id\": \"cohere:labels\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"cohere:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"endpoints\": {\n          \"@id\": \"cohere:endpoints\",\n          \"@container\": \"@set\"\n        },\n        \"contextLength\": \"cohere:contextLength\",\n        \"tokenizerUrl\": {\n          \"@id\": \"cohere:tokenizerUrl\",\n          \"@type\": \"@id\"\n        },\n        \"finetuned\": \"cohere:finetuned\"\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"cohere:Dataset\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"datasetType\": \"cohere:datasetType\",\n        \"validationStatus\": \"cohere:validationStatus\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateModified\": {\n\
  \          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EmbedJob\": {\n      \"@id\": \"cohere:EmbedJob\",\n      \"@context\": {\n        \"jobId\": \"schema:identifier\",\n        \"status\": \"cohere:status\",\n        \"model\": \"cohere:model\",\n        \"name\": \"schema:name\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"inputDatasetId\": \"cohere:inputDatasetId\",\n        \"outputDatasetId\": \"cohere:outputDatasetId\"\n      }\n    },\n\n    \"Tool\": {\n      \"@id\": \"cohere:Tool\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"parameters\": \"cohere:parameters\"\n      }\n    },\n\n    \"ToolCall\": {\n      \"@id\": \"cohere:ToolCall\",\n      \"@context\": {\n        \"identifier\": \"schema:identifier\",\n        \"functionName\": \"cohere:functionName\"\
  ,\n        \"arguments\": \"cohere:arguments\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/json-ld/cohere-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
