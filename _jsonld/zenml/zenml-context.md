---
api_specs:
- filename: zenml-openapi.yml
  format: yaml
  label: ZenML OSS REST API
  slug: zenml-oss-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/openapi/zenml-openapi.yml
class_count: 23
classes:
- Pipeline
- PipelineRun
- Stack
- StackComponent
- Artifact
- Model
- ModelVersion
- Deployment
- Schedule
- Project
- ServiceConnector
- id
- name
- description
- version
- license
- created
- updated
- start_time
- end_time
- status
- components
- uri
context_file: json-ld/zenml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/json-ld/zenml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zenml from ZenML.
layout: jsonld
name: Zenml Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: zenml
  uri: https://zenml.io/vocab#
properties:
- container: ''
  name: pipeline_id
  type: reference
- container: ''
  name: stack_id
  type: reference
- container: ''
  name: model_id
  type: reference
property_count: 3
provider_name: ZenML
provider_slug: zenml
slug: zenml-context
source_filename: zenml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"zenml\": \"https://zenml.io/vocab#\",\n    \"Pipeline\": \"zenml:Pipeline\",\n    \"PipelineRun\": \"zenml:PipelineRun\",\n    \"Stack\": \"zenml:Stack\",\n    \"StackComponent\": \"zenml:StackComponent\",\n    \"Artifact\": \"zenml:Artifact\",\n    \"Model\": \"zenml:Model\",\n    \"ModelVersion\": \"zenml:ModelVersion\",\n    \"Deployment\": \"zenml:Deployment\",\n    \"Schedule\": \"zenml:Schedule\",\n    \"Project\": \"zenml:Project\",\n    \"ServiceConnector\": \"zenml:ServiceConnector\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"license\": \"schema:license\",\n    \"created\": \"schema:dateCreated\",\n    \"updated\": \"schema:dateModified\",\n    \"start_time\": \"schema:startTime\",\n    \"end_time\": \"schema:endTime\",\n    \"status\": \"zenml:status\",\n    \"pipeline_id\"\
  : { \"@id\": \"zenml:pipeline\", \"@type\": \"@id\" },\n    \"stack_id\": { \"@id\": \"zenml:stack\", \"@type\": \"@id\" },\n    \"model_id\": { \"@id\": \"zenml:model\", \"@type\": \"@id\" },\n    \"components\": \"zenml:components\",\n    \"uri\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/json-ld/zenml-context.jsonld
tags:
- AI
- Machine Learning
- MLOps
- LLMOps
- Pipelines
- Open Source
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
