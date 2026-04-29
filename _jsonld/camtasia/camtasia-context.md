---
class_count: 0
classes: []
context_file: json-ld/camtasia-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/json-ld/camtasia-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Camtasia from Camtasia.
layout: jsonld
name: Camtasia Context
namespaces:
- prefix: camtasia
  uri: https://api.techsmith.com/schemas/camtasia/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Template
  type: ''
- container: ''
  name: Library
  type: ''
- container: ''
  name: Track
  type: ''
- container: ''
  name: Recording
  type: ''
- container: ''
  name: Production
  type: ''
property_count: 7
provider_name: Camtasia
provider_slug: camtasia
slug: camtasia-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"camtasia\": \"https://api.techsmith.com/schemas/camtasia/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Asset\": {\n      \"@id\": \"camtasia:Asset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"camtasia:assetType\",\n        \"format\": \"schema:encodingFormat\",\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnailUrl\"\
  : {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": \"schema:keywords\",\n        \"libraryId\": \"camtasia:libraryId\",\n        \"categoryId\": \"camtasia:categoryId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"camtasia:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"camtasia:projectStatus\",\n        \"resolution\": \"camtasia:resolution\",\n        \"frameRate\": {\n          \"@id\": \"camtasia:frameRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"duration\"\
  : {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"trackCount\": {\n          \"@id\": \"camtasia:trackCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"templateId\": \"camtasia:templateId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Template\": {\n      \"@id\": \"camtasia:Template\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"previewUrl\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"resolution\": \"camtasia:resolution\"\
  ,\n        \"frameRate\": {\n          \"@id\": \"camtasia:frameRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"builtIn\": {\n          \"@id\": \"camtasia:builtIn\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Library\": {\n      \"@id\": \"camtasia:Library\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"camtasia:libraryType\",\n        \"assetCount\": {\n          \"@id\": \"camtasia:assetCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Track\": {\n      \"@id\": \"camtasia:Track\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"camtasia:trackType\",\n        \"order\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"visible\": {\n          \"@id\": \"camtasia:visible\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"locked\": {\n          \"@id\": \"camtasia:locked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"muted\": {\n          \"@id\": \"camtasia:muted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"opacity\": {\n          \"@id\": \"camtasia:opacity\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Recording\": {\n      \"@id\": \"camtasia:Recording\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"format\"\
  : \"schema:encodingFormat\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"resolution\": \"camtasia:resolution\",\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hasWebcam\": {\n          \"@id\": \"camtasia:hasWebcam\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasAudio\": {\n          \"@id\": \"camtasia:hasAudio\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasCursorData\": {\n          \"@id\": \"camtasia:hasCursorData\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Production\": {\n      \"@id\": \"camtasia:Production\",\n      \"@context\": {\n        \"projectId\": \"camtasia:projectId\",\n        \"status\": \"camtasia:productionStatus\"\
  ,\n        \"progress\": {\n          \"@id\": \"camtasia:progress\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"format\": \"schema:encodingFormat\",\n        \"resolution\": \"camtasia:resolution\",\n        \"frameRate\": {\n          \"@id\": \"camtasia:frameRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"quality\": \"camtasia:quality\",\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"downloadUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"startedAt\": {\n          \"@id\": \"camtasia:startedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"camtasia:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/camtasia/refs/heads/main/json-ld/camtasia-context.jsonld
tags:
- Screen Recording
- Video Editing
- Tutorial Creation
- E-Learning
- Screencast
- oEmbed
- SDK
- JSON-LD
- Linked Data
- Semantic Web
---
