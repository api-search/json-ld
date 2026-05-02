---
api_specs:
- filename: midjourney-image-generation-openapi.yml
  format: yaml
  label: Midjourney Image Generation API
  slug: image-generation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/midjourney/refs/heads/main/openapi/midjourney-image-generation-openapi.yml
class_count: 0
classes: []
context_file: json-ld/midjourney-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/midjourney/refs/heads/main/json-ld/midjourney-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Midjourney from midjourney.
layout: jsonld
name: Midjourney Context
namespaces:
- prefix: mj
  uri: https://api.midjourney.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ImageGenerationJob
  type: ''
- container: ''
  name: GeneratedImage
  type: ''
- container: ''
  name: GenerationParameters
  type: ''
- container: ''
  name: PromptSuggestion
  type: ''
- container: set
  name: images
  type: ''
- container: set
  name: prompts
  type: ''
property_count: 6
provider_name: midjourney
provider_slug: midjourney
slug: midjourney-context
source_filename: midjourney-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mj\": \"https://api.midjourney.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ImageGenerationJob\": {\n      \"@id\": \"mj:ImageGenerationJob\",\n      \"@context\": {\n        \"jobId\": \"mj:jobId\",\n        \"jobType\": \"mj:jobType\",\n        \"status\": \"schema:actionStatus\",\n        \"progress\": \"mj:progress\",\n        \"prompt\": \"mj:prompt\",\n        \"parentJobId\": {\n          \"@id\": \"mj:parentJobId\",\n          \"@type\": \"@id\"\n        },\n        \"imageIndex\": \"mj:imageIndex\",\n        \"result\": \"schema:result\",\n        \"error\": \"schema:error\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"completedAt\": {\n          \"@id\": \"mj:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GeneratedImage\": {\n      \"@id\": \"mj:GeneratedImage\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"index\": \"mj:gridIndex\",\n        \"width\": \"schema:width\",\n        \"height\": \"schema:height\",\n        \"contentType\": \"schema:encodingFormat\"\n      }\n    },\n\n    \"GenerationParameters\": {\n      \"@id\": \"mj:GenerationParameters\",\n      \"@context\": {\n        \"aspectRatio\": \"mj:aspectRatio\",\n        \"modelVersion\": \"schema:softwareVersion\",\n        \"processMode\": \"mj:processMode\",\n        \"quality\": \"mj:quality\",\n        \"stylize\": \"mj:stylize\",\n        \"chaos\": \"mj:chaos\",\n        \"seed\": \"mj:seed\",\n        \"negativePrompt\": \"mj:negativePrompt\"\n      }\n    },\n\n    \"PromptSuggestion\"\
  : {\n      \"@id\": \"mj:PromptSuggestion\",\n      \"@context\": {\n        \"text\": \"schema:text\",\n        \"sourceImage\": {\n          \"@id\": \"mj:sourceImage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"images\": {\n      \"@id\": \"mj:images\",\n      \"@container\": \"@set\"\n    },\n    \"prompts\": {\n      \"@id\": \"mj:prompts\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/midjourney/refs/heads/main/json-ld/midjourney-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
