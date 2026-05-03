---
api_specs:
- filename: tensorflow-serving-openapi.yml
  format: yaml
  label: TensorFlow Serving REST API
  slug: tensorflow-serving-rest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml
class_count: 4
classes:
- Organization
- name
- description
- url
context_file: json-ld/tensorflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/json-ld/tensorflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tensorflow from TensorFlow.
layout: jsonld
name: Tensorflow Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tf
  uri: https://www.tensorflow.org/api_docs/python/tf#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: TensorFlowModel
  type: reference
- container: ''
  name: ModelVersion
  type: reference
- container: ''
  name: ModelSignature
  type: reference
- container: ''
  name: PredictionRequest
  type: reference
- container: ''
  name: PredictionResponse
  type: reference
- container: ''
  name: model_name
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: signature_name
  type: string
- container: list
  name: instances
  type: ''
- container: ''
  name: inputs
  type: '@json'
- container: list
  name: predictions
  type: ''
- container: ''
  name: outputs
  type: '@json'
- container: ''
  name: state
  type: '@vocab'
- container: list
  name: model_version_status
  type: ''
- container: ''
  name: machineLearning
  type: ''
property_count: 15
provider_name: TensorFlow
provider_slug: tensorflow
slug: tensorflow-context
source_filename: tensorflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tf\": \"https://www.tensorflow.org/api_docs/python/tf#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"TensorFlowModel\": {\n      \"@id\": \"tf:Model\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A TensorFlow machine learning model\"\n    },\n    \"ModelVersion\": {\n      \"@id\": \"tf:ModelVersion\",\n      \"@type\": \"@id\"\n    },\n    \"ModelSignature\": {\n      \"@id\": \"tf:Signature\",\n      \"@type\": \"@id\"\n    },\n    \"PredictionRequest\": {\n      \"@id\": \"tf:PredictRequest\",\n      \"@type\": \"@id\"\n    },\n    \"PredictionResponse\": {\n      \"@id\": \"tf:PredictResponse\",\n      \"@type\": \"@id\"\n    },\n\n    \"model_name\": {\n      \"@id\": \"tf:modelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"tf:version\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"signature_name\": {\n      \"@id\": \"tf:signatureName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instances\": {\n      \"@id\": \"tf:instances\",\n      \"@container\": \"@list\"\n    },\n    \"inputs\": {\n      \"@id\": \"tf:inputs\",\n      \"@type\": \"@json\"\n    },\n    \"predictions\": {\n      \"@id\": \"tf:predictions\",\n      \"@container\": \"@list\"\n    },\n    \"outputs\": {\n      \"@id\": \"tf:outputs\",\n      \"@type\": \"@json\"\n    },\n    \"state\": {\n      \"@id\": \"tf:state\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"AVAILABLE\": \"tf:AVAILABLE\",\n        \"LOADING\": \"tf:LOADING\",\n        \"UNLOADING\": \"tf:UNLOADING\",\n        \"START\": \"tf:START\",\n        \"END\": \"tf:END\",\n        \"UNKNOWN\": \"tf:UNKNOWN\"\n      }\n    },\n    \"model_version_status\": {\n      \"@id\": \"tf:modelVersionStatus\",\n      \"@container\": \"@list\"\n    },\n\n    \"machineLearning\": {\n      \"\
  @id\": \"schema:SoftwareApplication\",\n      \"rdfs:comment\": \"Machine learning platform\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/json-ld/tensorflow-context.jsonld
tags:
- AI
- Deep Learning
- JavaScript
- Machine Learning
- Model Serving
- Neural Networks
- Open Source
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
