---
api_specs:
- filename: riverside-business-openapi.yml
  format: yaml
  label: Riverside Business API
  slug: riverside-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/openapi/riverside-business-openapi.yml
class_count: 25
classes:
- Recording
- id
- name
- status
- created_date
- studio_id
- studio_name
- project_id
- project_name
- tracks
- Track
- type
- files
- download_url
- size
- transcription
- srt_url
- txt_url
- Production
- Studio
- Project
- num_recordings
- Export
- WebinarRegistrant
- email
context_file: json-ld/riverside-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/json-ld/riverside-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Riverside from Riverside.
layout: jsonld
name: Riverside Context
namespaces:
- prefix: riverside
  uri: https://api-evangelist.github.io/riverside/vocab#
properties: []
property_count: 0
provider_name: Riverside
provider_slug: riverside
slug: riverside-context
source_filename: riverside-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"riverside\": \"https://api-evangelist.github.io/riverside/vocab#\",\n    \"Recording\": \"schema:MediaObject\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"status\": \"schema:actionStatus\",\n    \"created_date\": \"schema:dateCreated\",\n    \"studio_id\": \"riverside:studioId\",\n    \"studio_name\": \"riverside:studioName\",\n    \"project_id\": \"riverside:projectId\",\n    \"project_name\": \"riverside:projectName\",\n    \"tracks\": \"riverside:tracks\",\n    \"Track\": \"schema:AudioObject\",\n    \"type\": \"schema:encodingFormat\",\n    \"files\": \"schema:associatedMedia\",\n    \"download_url\": \"schema:contentUrl\",\n    \"size\": \"schema:contentSize\",\n    \"transcription\": \"schema:Transcript\",\n    \"srt_url\": \"riverside:srtUrl\",\n    \"txt_url\": \"riverside:txtUrl\",\n    \"Production\": \"schema:CreativeWorkSeason\",\n    \"Studio\": \"riverside:Studio\"\
  ,\n    \"Project\": \"riverside:Project\",\n    \"num_recordings\": \"riverside:recordingCount\",\n    \"Export\": \"riverside:Export\",\n    \"WebinarRegistrant\": \"schema:Person\",\n    \"email\": \"schema:email\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/riverside/refs/heads/main/json-ld/riverside-context.jsonld
tags:
- Podcast
- Video Recording
- Media
- Content Creation
- Audio
- JSON-LD
- Linked Data
- Semantic Web
---
