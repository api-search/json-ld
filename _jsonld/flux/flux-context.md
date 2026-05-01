---
api_specs:
- filename: flux-image-generation-openapi.yml
  format: yaml
  label: Flux Image Generation API
  slug: flux-image-generation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/openapi/flux-image-generation-openapi.yml
- filename: flux-image-editing-openapi.yml
  format: yaml
  label: Flux Image Editing API
  slug: flux-image-editing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/openapi/flux-image-editing-openapi.yml
class_count: 0
classes: []
context_file: json-ld/flux-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/json-ld/flux-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Flux from Flux.
layout: jsonld
name: Flux Context
namespaces:
- prefix: flux
  uri: https://docs.bfl.ai/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: oa
  uri: http://www.w3.org/ns/oa#
properties:
- container: ''
  name: ImageGenerationRequest
  type: ''
- container: ''
  name: ImageEditRequest
  type: ''
- container: ''
  name: GenerationTask
  type: ''
- container: ''
  name: GenerationResult
  type: ''
- container: ''
  name: FluxModel
  type: ''
property_count: 5
provider_name: Flux
provider_slug: flux
slug: flux-context
source_filename: flux-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"flux\": \"https://docs.bfl.ai/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"oa\": \"http://www.w3.org/ns/oa#\",\n\n    \"ImageGenerationRequest\": {\n      \"@id\": \"flux:ImageGenerationRequest\",\n      \"@context\": {\n        \"prompt\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"aspect_ratio\": {\n          \"@id\": \"schema:size\",\n          \"@type\": \"xsd:string\"\n        },\n        \"steps\": {\n          \"@id\": \"flux:inferenceSteps\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"guidance\": {\n \
  \         \"@id\": \"flux:guidanceScale\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"seed\": {\n          \"@id\": \"flux:randomSeed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"output_format\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"safety_tolerance\": {\n          \"@id\": \"flux:safetyLevel\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"ImageEditRequest\": {\n      \"@id\": \"flux:ImageEditRequest\",\n      \"@context\": {\n        \"prompt\": {\n          \"@id\": \"oa:hasBody\",\n          \"@type\": \"xsd:string\"\n        },\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"xsd:string\"\n        },\n        \"steps\": {\n          \"@id\": \"flux:inferenceSteps\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"guidance\": {\n          \"@id\": \"flux:guidanceScale\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"seed\": {\n          \"@id\": \"flux:randomSeed\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"GenerationTask\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:actionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"polling_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"GenerationResult\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@context\": {\n        \"sample\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"prompt\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"seed\": {\n          \"@id\": \"flux:randomSeed\",\n          \"@type\": \"xsd:integer\"\n  \
  \      }\n      }\n    },\n\n    \"FluxModel\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n        \"description\": \"schema:description\",\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"provider\": {\n          \"@id\": \"schema:provider\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/json-ld/flux-context.jsonld
tags:
- AI
- Image Generation
- Machine Learning
- Open Source
- Text to Image
- JSON-LD
- Linked Data
- Semantic Web
---
