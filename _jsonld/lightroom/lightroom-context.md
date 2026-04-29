---
class_count: 0
classes: []
context_file: json-ld/lightroom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/json-ld/lightroom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Lightroom from Adobe Lightroom.
layout: jsonld
name: Lightroom Context
namespaces:
- prefix: lr
  uri: https://lr.adobe.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: exif
  uri: http://ns.adobe.com/exif/1.0/
properties:
- container: ''
  name: Catalog
  type: ''
- container: ''
  name: Album
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Rendition
  type: ''
- container: ''
  name: DevelopSettings
  type: ''
property_count: 5
provider_name: Adobe Lightroom
provider_slug: lightroom
slug: lightroom-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lr\": \"https://lr.adobe.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"exif\": \"http://ns.adobe.com/exif/1.0/\",\n\n    \"Catalog\": {\n      \"@id\": \"lr:Catalog\",\n      \"@context\": {\n        \"catalogId\": \"lr:catalogId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"userCreated\": {\n          \"@id\": \"lr:userCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"userUpdated\": {\n          \"@id\": \"lr:userUpdated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  assets\": {\n          \"@id\": \"lr:assets\",\n          \"@type\": \"@id\"\n        },\n        \"albums\": {\n          \"@id\": \"lr:albums\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Album\": {\n      \"@id\": \"lr:Album\",\n      \"@context\": {\n        \"albumId\": \"lr:albumId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subtype\": \"lr:subtype\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"userCreated\": {\n          \"@id\": \"lr:userCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"userUpdated\": {\n          \"@id\": \"lr:userUpdated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"cover\": {\n          \"@id\": \"schema:image\",\n      \
  \    \"@type\": \"@id\"\n        },\n        \"parent\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"@id\"\n        },\n        \"assets\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"lr:Asset\",\n      \"@context\": {\n        \"assetId\": \"lr:assetId\",\n        \"subtype\": \"lr:subtype\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"captureDate\": {\n          \"@id\": \"exif:dateTimeOriginal\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"fileName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mimeType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n \
  \       },\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rating\": {\n          \"@id\": \"schema:ratingValue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"flag\": \"lr:flag\",\n        \"label\": \"lr:label\",\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"altitude\": {\n          \"@id\": \"schema:elevation\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"importSource\": \"lr:importSource\",\n        \"importedOnDevice\": \"lr:importedOnDevice\",\n        \"importTimestamp\": {\n          \"@id\": \"lr:importTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"master\": {\n          \"@id\": \"lr:master\",\n          \"@type\": \"@id\"\n        },\n        \"renditions\": {\n          \"@id\": \"lr:renditions\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Rendition\": {\n      \"@id\": \"lr:Rendition\",\n      \"@context\": {\n        \"renditionType\": \"lr:renditionType\",\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"contentType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentLength\": {\n          \"@id\": \"schema:contentSize\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"asset\": {\n          \"@id\": \"schema:isBasedOn\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DevelopSettings\": {\n      \"@id\": \"lr:DevelopSettings\",\n      \"@context\": {\n        \"exposure\": \"lr:exposure\",\n        \"contrast\": \"lr:contrast\",\n        \"highlights\": \"lr:highlights\",\n        \"shadows\": \"lr:shadows\",\n        \"whites\": \"lr:whites\",\n        \"blacks\": \"lr:blacks\",\n        \"clarity\": \"lr:clarity\",\n        \"vibrance\": \"lr:vibrance\",\n        \"saturation\": \"lr:saturation\",\n        \"temperature\": \"lr:temperature\",\n        \"tint\": \"lr:tint\",\n        \"whiteBalance\": \"lr:whiteBalance\"\n      }\n    }\n \
  \ }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/json-ld/lightroom-context.jsonld
tags:
- Cloud Storage
- Image Editing
- Metadata
- Photo Management
- Photography
- JSON-LD
- Linked Data
- Semantic Web
---
