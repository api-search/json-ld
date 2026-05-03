---
api_specs:
- filename: rest_api.yaml
  format: yaml
  label: Triton HTTP/REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/triton-inference-server/server/blob/main/docs/protocol/rest_api.yaml
- filename: triton-metrics-openapi.yml
  format: yaml
  label: Triton Metrics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/openapi/triton-metrics-openapi.yml
class_count: 0
classes: []
context_file: json-ld/triton-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/json-ld/triton-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Triton from Triton Inference Server.
layout: jsonld
name: Triton Context
namespaces:
- prefix: triton
  uri: https://developer.nvidia.com/schemas/triton/
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
  name: Tensor
  type: ''
- container: ''
  name: InferenceRequest
  type: ''
- container: ''
  name: InferenceResponse
  type: ''
- container: ''
  name: ModelStatistics
  type: ''
- container: ''
  name: ServerMetadata
  type: ''
- container: ''
  name: InstanceGroup
  type: ''
- container: ''
  name: SharedMemoryRegion
  type: ''
- container: ''
  name: RepositoryEntry
  type: ''
property_count: 9
provider_name: Triton Inference Server
provider_slug: triton
slug: triton-context
source_filename: triton-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"triton\": \"https://developer.nvidia.com/schemas/triton/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"ml\": \"http://www.w3.org/ns/mls#\",\n\n    \"Model\": {\n      \"@id\": \"triton:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"platform\": \"triton:platform\",\n        \"backend\": \"triton:backend\",\n        \"maxBatchSize\": {\n          \"@id\": \"triton:maxBatchSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"versions\": \"triton:versions\",\n        \"inputs\": \"triton:inputs\",\n        \"outputs\": \"triton:outputs\",\n        \"instanceGroup\": \"triton:instanceGroup\",\n        \"dynamicBatching\": \"triton:dynamicBatching\",\n        \"sequenceBatching\": \"triton:sequenceBatching\"\n      }\n    },\n\n    \"Tensor\": {\n      \"@id\": \"triton:Tensor\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"datatype\": \"triton:datatype\",\n        \"shape\": \"triton:shape\",\n        \"data\": \"triton:data\"\n      }\n    },\n\n    \"InferenceRequest\": {\n      \"@id\": \"triton:InferenceRequest\",\n      \"@context\": {\n        \"requestId\": \"schema:identifier\",\n        \"inputs\": \"triton:inputs\",\n        \"outputs\": \"triton:outputs\",\n        \"sequenceId\": \"triton:sequenceId\",\n        \"sequenceStart\": {\n          \"@id\": \"triton:sequenceStart\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"sequenceEnd\": {\n          \"@id\": \"triton:sequenceEnd\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"priority\": {\n          \"@id\": \"triton:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"timeout\": {\n          \"@id\": \"triton:timeout\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"InferenceResponse\": {\n \
  \     \"@id\": \"triton:InferenceResponse\",\n      \"@context\": {\n        \"responseId\": \"schema:identifier\",\n        \"modelName\": \"triton:modelName\",\n        \"modelVersion\": \"triton:modelVersion\",\n        \"outputs\": \"triton:outputs\"\n      }\n    },\n\n    \"ModelStatistics\": {\n      \"@id\": \"triton:ModelStatistics\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"lastInference\": {\n          \"@id\": \"triton:lastInference\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"inferenceCount\": {\n          \"@id\": \"triton:inferenceCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"executionCount\": {\n          \"@id\": \"triton:executionCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ServerMetadata\": {\n      \"@id\": \"triton:ServerMetadata\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"\
  schema:softwareVersion\",\n        \"extensions\": \"triton:extensions\"\n      }\n    },\n\n    \"InstanceGroup\": {\n      \"@id\": \"triton:InstanceGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"kind\": \"triton:deviceKind\",\n        \"count\": {\n          \"@id\": \"triton:instanceCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"gpus\": \"triton:gpuDevices\"\n      }\n    },\n\n    \"SharedMemoryRegion\": {\n      \"@id\": \"triton:SharedMemoryRegion\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"key\": \"triton:sharedMemoryKey\",\n        \"offset\": {\n          \"@id\": \"triton:offset\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"byteSize\": {\n          \"@id\": \"triton:byteSize\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"RepositoryEntry\": {\n      \"@id\": \"triton:RepositoryEntry\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n\
  \        \"version\": \"schema:version\",\n        \"state\": \"triton:modelState\",\n        \"reason\": \"triton:stateReason\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/triton/refs/heads/main/json-ld/triton-context.jsonld
tags:
- AI
- Deep Learning
- Inference
- Machine Learning
- Model Serving
- NVIDIA
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
