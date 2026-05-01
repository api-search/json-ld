---
api_specs:
- filename: photos.yml
  format: yaml
  label: Google Photos Library API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-photos/refs/heads/main/openapi/photos.yml
class_count: 13
classes:
- MediaItem
- Album
- id
- description
- mimeType
- filename
- width
- height
- cameraMake
- cameraModel
- title
- coverPhotoBaseUrl
- mediaItemsCount
context_file: json-ld/photos.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-photos/refs/heads/main/json-ld/photos.jsonld
description: JSON-LD context defining the semantic vocabulary for Photos from Google Photos Library.
layout: jsonld
name: Photos Context
namespaces:
- prefix: gphotos
  uri: https://photoslibrary.googleapis.com/v1/
properties:
- container: ''
  name: productUrl
  type: reference
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: creationTime
  type: schema:DateTime
property_count: 3
provider_name: Google Photos Library
provider_slug: google-photos
slug: photos
source_filename: photos.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gphotos\": \"https://photoslibrary.googleapis.com/v1/\",\n    \"MediaItem\": \"gphotos:MediaItem\",\n    \"Album\": \"gphotos:Album\",\n    \"id\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n    \"productUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"mimeType\": \"schema:encodingFormat\",\n    \"filename\": \"schema:name\",\n    \"creationTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"cameraMake\": \"schema:manufacturer\",\n    \"cameraModel\": \"schema:model\",\n    \"title\": \"schema:name\",\n    \"coverPhotoBaseUrl\": \"schema:thumbnailUrl\",\n    \"mediaItemsCount\": \"schema:numberOfItems\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-photos/refs/heads/main/json-ld/photos.jsonld
tags:
- Albums
- Google
- Images
- Media
- Photos
- Sharing
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
