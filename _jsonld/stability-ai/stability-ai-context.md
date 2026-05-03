---
api_specs:
- filename: stability-ai-stable-image-generate-openapi.yml
  format: yaml
  label: Stability AI Stable Image Generate API
  slug: stable-image-generate
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-generate-openapi.yml
- filename: stability-ai-stable-image-edit-openapi.yml
  format: yaml
  label: Stability AI Stable Image Edit API
  slug: stable-image-edit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-edit-openapi.yml
- filename: stability-ai-stable-image-upscale-openapi.yml
  format: yaml
  label: Stability AI Stable Image Upscale API
  slug: stable-image-upscale
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-upscale-openapi.yml
- filename: stability-ai-stable-image-control-openapi.yml
  format: yaml
  label: Stability AI Stable Image Control API
  slug: stable-image-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-image-control-openapi.yml
- filename: stability-ai-stable-video-diffusion-openapi.yml
  format: yaml
  label: Stability AI Stable Video Diffusion API
  slug: stable-video-diffusion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-video-diffusion-openapi.yml
- filename: stability-ai-stable-fast-3d-openapi.yml
  format: yaml
  label: Stability AI Stable Fast 3D API
  slug: stable-fast-3d
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/openapi/stability-ai-stable-fast-3d-openapi.yml
class_count: 0
classes: []
context_file: json-ld/stability-ai-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/json-ld/stability-ai-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stability Ai from Stability AI.
layout: jsonld
name: Stability Ai Context
namespaces:
- prefix: stability
  uri: https://platform.stability.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ImageGeneration
  type: ''
- container: ''
  name: ImageEdit
  type: ''
- container: ''
  name: ImageUpscale
  type: ''
- container: ''
  name: ImageControl
  type: ''
- container: ''
  name: VideoGeneration
  type: ''
- container: ''
  name: ThreeDGeneration
  type: ''
- container: ''
  name: GenerativeModel
  type: ''
- container: ''
  name: ApiKey
  type: ''
property_count: 8
provider_name: Stability AI
provider_slug: stability-ai
slug: stability-ai-context
source_filename: stability-ai-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"stability\": \"https://platform.stability.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ImageGeneration\": {\n      \"@id\": \"stability:ImageGeneration\",\n      \"@context\": {\n        \"prompt\": \"stability:prompt\",\n        \"negativePrompt\": \"stability:negativePrompt\",\n        \"aspectRatio\": \"stability:aspectRatio\",\n        \"outputFormat\": \"stability:outputFormat\",\n        \"seed\": \"stability:seed\",\n        \"model\": \"stability:model\",\n        \"mode\": \"stability:mode\",\n        \"strength\": \"stability:strength\",\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"result\": \"stability:result\",\n        \"finishReason\": \"stability:finishReason\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ImageEdit\": {\n      \"@id\": \"stability:ImageEdit\",\n      \"@context\": {\n        \"operation\": \"stability:editOperation\",\n        \"sourceImage\": {\n          \"@id\": \"stability:sourceImage\",\n          \"@type\": \"@id\"\n        },\n        \"maskImage\": {\n          \"@id\": \"stability:maskImage\",\n          \"@type\": \"@id\"\n        },\n        \"prompt\": \"stability:prompt\",\n        \"searchPrompt\": \"stability:searchPrompt\",\n        \"resultImage\": {\n          \"@id\": \"stability:resultImage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ImageUpscale\": {\n      \"@id\": \"stability:ImageUpscale\",\n      \"@context\": {\n        \"method\": \"stability:upscaleMethod\",\n        \"sourceImage\": {\n          \"@id\": \"stability:sourceImage\",\n          \"@type\": \"@id\"\n        },\n        \"prompt\": \"stability:prompt\",\n        \"resultImage\"\
  : {\n          \"@id\": \"stability:resultImage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ImageControl\": {\n      \"@id\": \"stability:ImageControl\",\n      \"@context\": {\n        \"controlMethod\": \"stability:controlMethod\",\n        \"controlStrength\": \"stability:controlStrength\",\n        \"fidelity\": \"stability:fidelity\",\n        \"referenceImage\": {\n          \"@id\": \"stability:referenceImage\",\n          \"@type\": \"@id\"\n        },\n        \"prompt\": \"stability:prompt\",\n        \"resultImage\": {\n          \"@id\": \"stability:resultImage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"VideoGeneration\": {\n      \"@id\": \"stability:VideoGeneration\",\n      \"@context\": {\n        \"sourceImage\": {\n          \"@id\": \"stability:sourceImage\",\n          \"@type\": \"@id\"\n        },\n        \"cfgScale\": \"stability:cfgScale\",\n        \"motionBucketId\": \"stability:motionBucketId\",\n        \"\
  seed\": \"stability:seed\",\n        \"resultVideo\": {\n          \"@id\": \"stability:resultVideo\",\n          \"@type\": \"@id\"\n        },\n        \"generationId\": \"stability:generationId\"\n      }\n    },\n\n    \"ThreeDGeneration\": {\n      \"@id\": \"stability:ThreeDGeneration\",\n      \"@context\": {\n        \"sourceImage\": {\n          \"@id\": \"stability:sourceImage\",\n          \"@type\": \"@id\"\n        },\n        \"textureResolution\": \"stability:textureResolution\",\n        \"foregroundRatio\": \"stability:foregroundRatio\",\n        \"remesh\": \"stability:remesh\",\n        \"resultModel\": {\n          \"@id\": \"stability:resultModel\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"GenerativeModel\": {\n      \"@id\": \"stability:GenerativeModel\",\n      \"@context\": {\n        \"modelId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\"\
  ,\n        \"capabilities\": {\n          \"@id\": \"stability:capabilities\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"stability:ApiKey\",\n      \"@context\": {\n        \"keyId\": \"schema:identifier\",\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"@id\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/json-ld/stability-ai-context.jsonld
tags:
- 3D Generation
- AI
- Generative AI
- Image Generation
- Image Editing
- Machine Learning
- Stable Diffusion
- Text to Image
- Video Generation
- JSON-LD
- Linked Data
- Semantic Web
---
