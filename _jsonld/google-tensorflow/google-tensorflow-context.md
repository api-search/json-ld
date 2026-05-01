---
api_specs:
- filename: tensorflow-serving-openapi.yml
  format: yaml
  label: TensorFlow Serving REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-tensorflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/json-ld/google-tensorflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Tensorflow from Google TensorFlow.
layout: jsonld
name: Google Tensorflow Context
namespaces:
- prefix: tf
  uri: https://www.tensorflow.org/ns/
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
  name: PredictRequest
  type: ''
- container: ''
  name: PredictResponse
  type: ''
- container: ''
  name: ServingSignature
  type: ''
property_count: 4
provider_name: Google TensorFlow
provider_slug: google-tensorflow
slug: google-tensorflow-context
source_filename: google-tensorflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"tf\": \"https://www.tensorflow.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Model\": {\n      \"@id\": \"tf:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"format\": \"tf:modelFormat\",\n        \"framework\": \"tf:framework\",\n        \"task\": \"tf:task\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:downloadUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PredictRequest\": {\n      \"@id\": \"tf:PredictRequest\",\n      \"@context\": {\n        \"signatureName\": \"tf:signatureName\",\n        \"instances\": \"tf:instances\",\n\
  \        \"inputs\": \"tf:inputs\"\n      }\n    },\n\n    \"PredictResponse\": {\n      \"@id\": \"tf:PredictResponse\",\n      \"@context\": {\n        \"predictions\": \"tf:predictions\",\n        \"outputs\": \"tf:outputs\",\n        \"modelSpec\": \"tf:modelSpec\"\n      }\n    },\n\n    \"ServingSignature\": {\n      \"@id\": \"tf:ServingSignature\",\n      \"@context\": {\n        \"signatureName\": \"tf:signatureName\",\n        \"methodName\": \"tf:methodName\",\n        \"inputs\": \"tf:signatureInputs\",\n        \"outputs\": \"tf:signatureOutputs\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/json-ld/google-tensorflow-context.jsonld
tags:
- AI
- Deep Learning
- Google
- Machine Learning
- Model Serving
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
