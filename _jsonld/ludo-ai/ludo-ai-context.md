---
api_specs:
- filename: ludo-ai-rest-api-openapi.yml
  format: yaml
  label: Ludo.ai REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/openapi/ludo-ai-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/ludo-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/json-ld/ludo-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ludo Ai from Ludo.ai.
layout: jsonld
name: Ludo Ai Context
namespaces:
- prefix: ludo
  uri: https://ludo.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: GameAsset
  type: ''
- container: ''
  name: Image
  type: ''
- container: ''
  name: Spritesheet
  type: ''
- container: ''
  name: Model3D
  type: ''
- container: ''
  name: Video
  type: ''
- container: ''
  name: AudioAsset
  type: ''
- container: ''
  name: AnimationPreset
  type: ''
property_count: 7
provider_name: Ludo.ai
provider_slug: ludo-ai
slug: ludo-ai-context
source_filename: ludo-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ludo\": \"https://ludo.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"GameAsset\": {\n      \"@id\": \"ludo:GameAsset\",\n      \"@context\": {\n        \"assetType\": \"ludo:assetType\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"requestId\": \"ludo:requestId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"creditsConsumed\": \"ludo:creditsConsumed\",\n        \"expiresAt\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Image\": {\n      \"@id\": \"ludo:Image\",\n      \"@context\": {\n        \"imageType\": \"ludo:imageType\",\n        \"artStyle\": \"ludo:artStyle\",\n        \"perspective\"\
  : \"ludo:perspective\",\n        \"aspectRatio\": \"ludo:aspectRatio\",\n        \"prompt\": \"ludo:prompt\"\n      }\n    },\n\n    \"Spritesheet\": {\n      \"@id\": \"ludo:Spritesheet\",\n      \"@context\": {\n        \"spritesheetUrl\": {\n          \"@id\": \"ludo:spritesheetUrl\",\n          \"@type\": \"@id\"\n        },\n        \"videoUrl\": {\n          \"@id\": \"ludo:videoUrl\",\n          \"@type\": \"@id\"\n        },\n        \"gifUrl\": {\n          \"@id\": \"ludo:gifUrl\",\n          \"@type\": \"@id\"\n        },\n        \"numFrames\": {\n          \"@id\": \"ludo:numFrames\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numCols\": {\n          \"@id\": \"ludo:numCols\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numRows\": {\n          \"@id\": \"ludo:numRows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"frameSize\": {\n          \"@id\": \"ludo:frameSize\",\n          \"@type\": \"xsd:integer\"\n        },\n   \
  \     \"loop\": {\n          \"@id\": \"ludo:loop\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"motionPrompt\": \"ludo:motionPrompt\",\n        \"individualFrameUrls\": {\n          \"@id\": \"ludo:individualFrameUrls\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Model3D\": {\n      \"@id\": \"ludo:Model3D\",\n      \"@context\": {\n        \"modelUrl\": {\n          \"@id\": \"ludo:modelUrl\",\n          \"@type\": \"@id\"\n        },\n        \"snapshots\": {\n          \"@id\": \"ludo:snapshots\",\n          \"@container\": \"@set\"\n        },\n        \"textureType\": \"ludo:textureType\",\n        \"textureSize\": {\n          \"@id\": \"ludo:textureSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"targetNumFaces\": {\n          \"@id\": \"ludo:targetNumFaces\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Video\": {\n      \"@id\": \"ludo:Video\",\n      \"@context\": {\n        \"duration\"\
  : {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"prompt\": \"ludo:prompt\",\n        \"model\": \"ludo:model\"\n      }\n    },\n\n    \"AudioAsset\": {\n      \"@id\": \"ludo:AudioAsset\",\n      \"@context\": {\n        \"audioType\": \"ludo:audioType\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"voicePresetId\": \"ludo:voicePresetId\",\n        \"emotion\": \"ludo:emotion\",\n        \"language\": {\n          \"@id\": \"schema:inLanguage\"\n        }\n      }\n    },\n\n    \"AnimationPreset\": {\n      \"@id\": \"ludo:AnimationPreset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"category\": \"schema:category\",\n        \"description\": \"schema:description\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"previewUrl\": {\n          \"@id\"\
  : \"ludo:previewUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/json-ld/ludo-ai-context.jsonld
tags:
- Artificial Intelligence
- Asset Generation
- Game Design
- Game Development
- JSON-LD
- Linked Data
- Semantic Web
---
