---
api_specs:
- filename: kserve-open-inference-protocol-openapi.yml
  format: yaml
  label: KServe Open Inference Protocol API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/openapi/kserve-open-inference-protocol-openapi.yml
class_count: 12
classes:
- id
- model_name
- model_version
- platform
- name
- shape
- datatype
- data
- parameters
- live
- ready
- tags
context_file: json-ld/scalable-inference-serving-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/refs/heads/main/json-ld/scalable-inference-serving-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Inference Serving from Scalable Inference Serving.
layout: jsonld
name: Scalable Inference Serving Context
namespaces:
- prefix: infer
  uri: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-ld/scalable-inference-serving-context.jsonld#
- prefix: kserve
  uri: https://kserve.github.io/ns/
- prefix: oip
  uri: https://github.com/kserve/open-inference-protocol/ns/
properties:
- container: ''
  name: InferenceRequest
  type: reference
- container: ''
  name: InferenceResponse
  type: reference
- container: ''
  name: ModelMetadata
  type: reference
- container: ''
  name: InferenceServer
  type: reference
- container: ''
  name: Tensor
  type: reference
- container: ''
  name: ModelRegistry
  type: reference
- container: ''
  name: InferenceService
  type: reference
- container: list
  name: inputs
  type: ''
- container: list
  name: outputs
  type: ''
- container: list
  name: versions
  type: ''
- container: list
  name: extensions
  type: ''
property_count: 11
provider_name: Scalable Inference Serving
provider_slug: scalable-inference-serving
slug: scalable-inference-serving-context
source_filename: scalable-inference-serving-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"infer\": \"https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-ld/scalable-inference-serving-context.jsonld#\",\n    \"kserve\": \"https://kserve.github.io/ns/\",\n    \"oip\": \"https://github.com/kserve/open-inference-protocol/ns/\",\n\n    \"InferenceRequest\": {\n      \"@id\": \"infer:InferenceRequest\",\n      \"@type\": \"@id\",\n      \"comment\": \"An OIP V2 inference request containing input tensors submitted to a model serving endpoint.\"\n    },\n    \"InferenceResponse\": {\n      \"@id\": \"infer:InferenceResponse\",\n      \"@type\": \"@id\",\n      \"comment\": \"The response from an OIP V2 inference request containing output tensors.\"\n    },\n    \"ModelMetadata\": {\n      \"@id\": \"infer:ModelMetadata\",\n      \"@type\": \"@id\",\n      \"comment\": \"Metadata describing a deployed model's inputs, outputs, and platform.\"\n \
  \   },\n    \"InferenceServer\": {\n      \"@id\": \"infer:InferenceServer\",\n      \"@type\": \"@id\",\n      \"comment\": \"An OIP-compliant server (KServe, Triton, BentoML) hosting model inference endpoints.\"\n    },\n    \"Tensor\": {\n      \"@id\": \"infer:Tensor\",\n      \"@type\": \"@id\",\n      \"comment\": \"A multi-dimensional array of data representing a model input or output.\"\n    },\n    \"ModelRegistry\": {\n      \"@id\": \"infer:ModelRegistry\",\n      \"@type\": \"@id\",\n      \"comment\": \"A versioned store of machine learning models and their metadata (e.g., MLflow Model Registry).\"\n    },\n    \"InferenceService\": {\n      \"@id\": \"kserve:InferenceService\",\n      \"@type\": \"@id\",\n      \"comment\": \"A KServe Custom Resource that deploys a model serving endpoint on Kubernetes.\"\n    },\n\n    \"id\": \"@id\",\n    \"model_name\": \"schema:name\",\n    \"model_version\": \"schema:version\",\n    \"platform\": \"infer:platform\",\n    \"inputs\":\
  \ {\n      \"@id\": \"infer:inputs\",\n      \"@container\": \"@list\"\n    },\n    \"outputs\": {\n      \"@id\": \"infer:outputs\",\n      \"@container\": \"@list\"\n    },\n    \"name\": \"schema:name\",\n    \"shape\": \"infer:shape\",\n    \"datatype\": \"infer:datatype\",\n    \"data\": \"infer:data\",\n    \"parameters\": \"infer:parameters\",\n    \"live\": \"infer:live\",\n    \"ready\": \"infer:ready\",\n    \"versions\": {\n      \"@id\": \"schema:version\",\n      \"@container\": \"@list\"\n    },\n    \"extensions\": {\n      \"@id\": \"infer:extensions\",\n      \"@container\": \"@list\"\n    },\n    \"tags\": \"schema:keywords\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/refs/heads/main/json-ld/scalable-inference-serving-context.jsonld
tags:
- AI
- CNCF
- Deployment
- Inference
- Kubernetes
- LLM
- Machine Learning
- Model Serving
- MLOps
- Scalability
- JSON-LD
- Linked Data
- Semantic Web
---
