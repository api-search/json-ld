---
api_specs:
- filename: youtube.yml
  format: yaml
  label: YouTube Data API v3
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-youtube/refs/heads/main/openapi/youtube.yml
class_count: 15
classes:
- Video
- Channel
- Playlist
- title
- description
- thumbnails
- channelTitle
- tags
- categoryId
- viewCount
- likeCount
- commentCount
- duration
- privacyStatus
- embeddable
context_file: json-ld/youtube.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-youtube/refs/heads/main/json-ld/youtube.jsonld
description: JSON-LD context defining the semantic vocabulary for Youtube from YouTube Data.
layout: jsonld
name: Youtube Context
namespaces:
- prefix: youtube
  uri: https://www.googleapis.com/youtube/v3/
properties:
- container: ''
  name: videoId
  type: reference
- container: ''
  name: channelId
  type: reference
- container: ''
  name: playlistId
  type: reference
- container: ''
  name: publishedAt
  type: schema:DateTime
property_count: 4
provider_name: YouTube Data
provider_slug: google-youtube
slug: youtube
source_filename: youtube.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"youtube\": \"https://www.googleapis.com/youtube/v3/\",\n    \"Video\": \"youtube:Video\",\n    \"Channel\": \"youtube:Channel\",\n    \"Playlist\": \"youtube:Playlist\",\n    \"videoId\": {\n      \"@id\": \"youtube:videoId\",\n      \"@type\": \"@id\"\n    },\n    \"channelId\": {\n      \"@id\": \"youtube:channelId\",\n      \"@type\": \"@id\"\n    },\n    \"playlistId\": {\n      \"@id\": \"youtube:playlistId\",\n      \"@type\": \"@id\"\n    },\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"publishedAt\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"thumbnails\": \"schema:thumbnailUrl\",\n    \"channelTitle\": \"schema:author\",\n    \"tags\": \"schema:keywords\",\n    \"categoryId\": \"schema:genre\",\n    \"viewCount\": \"schema:interactionCount\",\n    \"likeCount\": \"schema:userInteractionCount\",\n    \"commentCount\"\
  : \"schema:commentCount\",\n    \"duration\": \"schema:duration\",\n    \"privacyStatus\": \"schema:accessMode\",\n    \"embeddable\": \"schema:isAccessibleForFree\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-youtube/refs/heads/main/json-ld/youtube.jsonld
tags:
- Channels
- Google
- Media
- Playlists
- Search
- Streaming
- Video
- YouTube
- JSON-LD
- Linked Data
- Semantic Web
---
