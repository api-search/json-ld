---
api_specs:
- filename: qubrid-ai-inference-openapi.yml
  format: yaml
  label: Qubrid AI Inference API
  slug: inference
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-inference-openapi.yml
- filename: qubrid-ai-compute-openapi.yml
  format: yaml
  label: Qubrid AI Compute API
  slug: compute
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-compute-openapi.yml
- filename: qubrid-ai-fine-tuning-openapi.yml
  format: yaml
  label: Qubrid AI Fine-Tuning API
  slug: fine-tuning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-fine-tuning-openapi.yml
- filename: qubrid-ai-rag-openapi.yml
  format: yaml
  label: Qubrid AI RAG API
  slug: rag
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-rag-openapi.yml
class_count: 0
classes: []
context_file: json-ld/qubrid-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-ld/qubrid-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Qubrid Ai from Qubrid AI.
layout: jsonld
name: Qubrid Ai Context
namespaces:
- prefix: qubrid
  uri: https://platform.qubrid.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Model
  type: ''
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: ComputeInstance
  type: ''
- container: ''
  name: GpuType
  type: ''
- container: ''
  name: FineTuningJob
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: KnowledgeBase
  type: ''
- container: ''
  name: Document
  type: ''
property_count: 8
provider_name: Qubrid AI
provider_slug: qubrid-ai
slug: qubrid-ai-context
source_filename: qubrid-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"qubrid\": \"https://platform.qubrid.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Model\": {\n      \"@id\": \"qubrid:Model\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"ownedBy\": \"schema:creator\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ChatCompletion\": {\n      \"@id\": \"qubrid:ChatCompletion\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"model\": \"qubrid:usesModel\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"choices\": {\n          \"@id\": \"qubrid:choices\",\n         \
  \ \"@container\": \"@set\"\n        },\n        \"promptTokens\": \"qubrid:promptTokens\",\n        \"completionTokens\": \"qubrid:completionTokens\",\n        \"totalTokens\": \"qubrid:totalTokens\"\n      }\n    },\n\n    \"ComputeInstance\": {\n      \"@id\": \"qubrid:ComputeInstance\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"status\": \"qubrid:instanceStatus\",\n        \"gpuType\": \"qubrid:gpuType\",\n        \"gpuCount\": \"qubrid:gpuCount\",\n        \"region\": \"schema:locationCreated\",\n        \"template\": \"qubrid:template\",\n        \"sshHost\": \"qubrid:sshHost\",\n        \"jupyterUrl\": {\n          \"@id\": \"qubrid:jupyterUrl\",\n          \"@type\": \"@id\"\n        },\n        \"costPerHour\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n     \
  \   }\n      }\n    },\n\n    \"GpuType\": {\n      \"@id\": \"qubrid:GpuType\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"manufacturer\": \"schema:manufacturer\",\n        \"memoryGb\": \"qubrid:memoryGb\",\n        \"pricePerHour\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"available\": \"schema:availability\",\n        \"regions\": {\n          \"@id\": \"qubrid:availableRegions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"FineTuningJob\": {\n      \"@id\": \"qubrid:FineTuningJob\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"qubrid:jobStatus\",\n        \"baseModel\": \"qubrid:baseModel\",\n        \"datasetId\": \"qubrid:usesDataset\",\n        \"taskType\": \"qubrid:taskType\",\n        \"fineTunedModel\": \"qubrid:producesModel\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"qubrid:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"qubrid:Dataset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"sizeBytes\": \"schema:contentSize\",\n        \"rowCount\": \"qubrid:rowCount\",\n        \"columns\": {\n          \"@id\": \"qubrid:columns\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"KnowledgeBase\": {\n      \"@id\": \"qubrid:KnowledgeBase\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"embeddingModel\": \"qubrid:embeddingModel\",\n        \"documentCount\": \"qubrid:documentCount\"\
  ,\n        \"chunkCount\": \"qubrid:chunkCount\",\n        \"status\": \"qubrid:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"qubrid:Document\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"sizeBytes\": \"schema:contentSize\",\n        \"format\": \"schema:encodingFormat\",\n        \"chunkCount\": \"qubrid:chunkCount\",\n        \"status\": \"qubrid:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-ld/qubrid-ai-context.jsonld
tags:
- Artificial Intelligence
- Cloud Computing
- GPU
- Inference
- Large Language Models
- Machine Learning
- NVIDIA
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
