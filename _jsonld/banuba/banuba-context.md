---
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/banuba-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/banuba/refs/heads/main/json-ld/banuba-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Banuba from Banuba.
layout: jsonld
name: Banuba Context
namespaces:
- prefix: banuba
  uri: https://www.banuba.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: FaceARSDK
  type: reference
- container: ''
  name: AREffect
  type: reference
- container: ''
  name: BeautyFilter
  type: reference
- container: ''
  name: FaceTracking
  type: reference
- container: ''
  name: BackgroundSegmentation
  type: reference
- container: ''
  name: VirtualTryOn
  type: reference
- container: ''
  name: FaceLiveness
  type: reference
- container: ''
  name: VideoEditorSDK
  type: reference
- container: ''
  name: AvatarSDK
  type: reference
- container: ''
  name: effectId
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: faceCount
  type: integer
- container: ''
  name: isLive
  type: boolean
- container: ''
  name: confidence
  type: decimal
property_count: 14
provider_name: Banuba
provider_slug: banuba
slug: banuba-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"banuba\": \"https://www.banuba.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FaceARSDK\": {\n      \"@id\": \"banuba:FaceARSDK\",\n      \"@type\": \"@id\"\n    },\n    \"AREffect\": {\n      \"@id\": \"banuba:AREffect\",\n      \"@type\": \"@id\"\n    },\n    \"BeautyFilter\": {\n      \"@id\": \"banuba:BeautyFilter\",\n      \"@type\": \"@id\"\n    },\n    \"FaceTracking\": {\n      \"@id\": \"banuba:FaceTracking\",\n      \"@type\": \"@id\"\n    },\n    \"BackgroundSegmentation\": {\n      \"@id\": \"banuba:BackgroundSegmentation\",\n      \"@type\": \"@id\"\n    },\n    \"VirtualTryOn\": {\n      \"@id\": \"banuba:VirtualTryOn\",\n      \"@type\": \"@id\"\n    },\n    \"FaceLiveness\": {\n      \"@id\": \"banuba:FaceLiveness\",\n      \"@type\": \"@id\"\n    },\n    \"VideoEditorSDK\": {\n      \"@id\": \"banuba:VideoEditorSDK\",\n      \"@type\": \"\
  @id\"\n    },\n    \"AvatarSDK\": {\n      \"@id\": \"banuba:AvatarSDK\",\n      \"@type\": \"@id\"\n    },\n    \"effectId\": {\n      \"@id\": \"banuba:effectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"banuba:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faceCount\": {\n      \"@id\": \"banuba:faceCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isLive\": {\n      \"@id\": \"banuba:isLive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"confidence\": {\n      \"@id\": \"banuba:confidence\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/banuba/refs/heads/main/json-ld/banuba-context.jsonld
tags:
- AR
- Augmented Reality
- Beauty
- Face Recognition
- Facial
- SDK
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
