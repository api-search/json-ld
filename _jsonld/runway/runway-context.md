---
api_specs:
- filename: runway-video-generation-openapi.yml
  format: yaml
  label: Runway Video Generation API
  slug: video-generation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-video-generation-openapi.yml
- filename: runway-image-generation-openapi.yml
  format: yaml
  label: Runway Image Generation API
  slug: image-generation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-image-generation-openapi.yml
- filename: runway-characters-openapi.yml
  format: yaml
  label: Runway Characters API
  slug: characters
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/openapi/runway-characters-openapi.yml
class_count: 0
classes: []
context_file: json-ld/runway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/json-ld/runway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Runway from Runway.
layout: jsonld
name: Runway Context
namespaces:
- prefix: runway
  uri: https://api.dev.runwayml.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: GenerationTask
  type: ''
- container: ''
  name: Avatar
  type: ''
- container: ''
  name: RealtimeSession
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: Upload
  type: ''
- container: ''
  name: VideoGeneration
  type: ''
- container: ''
  name: ImageGeneration
  type: ''
property_count: 7
provider_name: Runway
provider_slug: runway
slug: runway-context
source_filename: runway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"runway\": \"https://api.dev.runwayml.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"GenerationTask\": {\n      \"@id\": \"runway:GenerationTask\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"runway:taskStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"output\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"failure\": \"runway:failureReason\",\n        \"model\": \"runway:model\",\n        \"promptText\": \"runway:promptText\",\n        \"promptImage\": {\n          \"@id\": \"runway:promptImage\",\n          \"@type\": \"@id\"\n        },\n        \"promptVideo\": {\n          \"@id\": \"runway:promptVideo\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"duration\": \"schema:duration\",\n        \"ratio\": \"runway:aspectRatio\"\n      }\n    },\n\n    \"Avatar\": {\n      \"@id\": \"runway:Avatar\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"referenceImage\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"personality\": \"runway:personality\",\n        \"voice\": \"runway:voiceConfig\",\n        \"openingMessage\": \"runway:openingMessage\",\n        \"documentIds\": {\n          \"@id\": \"runway:knowledgeDocuments\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RealtimeSession\": {\n      \"@id\": \"runway:RealtimeSession\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"runway:sessionStatus\"\
  ,\n        \"serverUrl\": {\n          \"@id\": \"runway:serverUrl\",\n          \"@type\": \"@id\"\n        },\n        \"token\": \"runway:sessionToken\",\n        \"roomName\": \"runway:roomName\",\n        \"maxSessionDurationSeconds\": \"runway:maxSessionDuration\",\n        \"model\": \"runway:model\"\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"runway:Document\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"content\": \"schema:text\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Upload\": {\n      \"@id\": \"runway:Upload\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"uploadUrl\": {\n          \"@id\": \"runway:uploadUrl\",\n          \"@type\": \"@id\"\n        },\n        \"filename\": \"schema:name\"\n      }\n    },\n\n    \"VideoGeneration\": {\n      \"@id\": \"runway:VideoGeneration\"\
  ,\n      \"@context\": {\n        \"model\": \"runway:model\",\n        \"promptText\": \"runway:promptText\",\n        \"promptImage\": {\n          \"@id\": \"runway:promptImage\",\n          \"@type\": \"@id\"\n        },\n        \"duration\": \"schema:duration\",\n        \"ratio\": \"runway:aspectRatio\"\n      }\n    },\n\n    \"ImageGeneration\": {\n      \"@id\": \"runway:ImageGeneration\",\n      \"@context\": {\n        \"model\": \"runway:model\",\n        \"promptText\": \"runway:promptText\",\n        \"ratio\": \"runway:aspectRatio\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/runway/refs/heads/main/json-ld/runway-context.jsonld
tags:
- Video Generation
- Image Generation
- Artificial Intelligence
- Machine Learning
- Generative AI
- Avatars
- Characters
- WebRTC
- Creative Tools
- JSON-LD
- Linked Data
- Semantic Web
---
