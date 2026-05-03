---
api_specs:
- filename: salad-transcription-api-openapi.yml
  format: yaml
  label: Salad Transcription API
  slug: salad-transcription-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/openapi/salad-transcription-api-openapi.yml
class_count: 6
classes:
- id
- input
- output
- status
- events
- metadata
context_file: json-ld/salad-transcription-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/json-ld/salad-transcription-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salad Transcription Api from Salad Transcription API.
layout: jsonld
name: Salad Transcription Api Context
namespaces:
- prefix: salad
  uri: https://salad.com/transcription/vocab#
properties:
- container: ''
  name: TranscriptionJob
  type: reference
- container: ''
  name: TranscriptionInput
  type: ''
- container: ''
  name: TranscriptionOutput
  type: ''
- container: ''
  name: TranscriptSegment
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: language_code
  type: ''
- container: ''
  name: diarization
  type: boolean
- container: ''
  name: word_level_timestamps
  type: boolean
- container: ''
  name: srt
  type: boolean
- container: list
  name: segments
  type: ''
- container: ''
  name: start
  type: decimal
- container: ''
  name: end
  type: decimal
- container: ''
  name: text
  type: ''
- container: ''
  name: speaker
  type: ''
- container: ''
  name: score
  type: decimal
- container: ''
  name: duration
  type: ''
- container: ''
  name: srt_content
  type: ''
- container: ''
  name: create_time
  type: dateTime
- container: ''
  name: update_time
  type: dateTime
property_count: 19
provider_name: Salad Transcription API
provider_slug: salad-transcription-api
slug: salad-transcription-api-context
source_filename: salad-transcription-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"salad\": \"https://salad.com/transcription/vocab#\",\n    \"TranscriptionJob\": {\n      \"@id\": \"salad:TranscriptionJob\",\n      \"@type\": \"@id\"\n    },\n    \"TranscriptionInput\": {\n      \"@id\": \"salad:TranscriptionInput\"\n    },\n    \"TranscriptionOutput\": {\n      \"@id\": \"salad:TranscriptionOutput\"\n    },\n    \"TranscriptSegment\": {\n      \"@id\": \"salad:TranscriptSegment\"\n    },\n    \"id\": \"@id\",\n    \"input\": \"salad:input\",\n    \"output\": \"salad:output\",\n    \"status\": \"salad:status\",\n    \"events\": \"salad:events\",\n    \"metadata\": \"salad:metadata\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"language_code\": {\n      \"@id\": \"schema:inLanguage\"\n    },\n    \"diarization\": {\n      \"@id\": \"salad:diarization\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"word_level_timestamps\": {\n      \"@id\"\
  : \"salad:wordLevelTimestamps\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"srt\": {\n      \"@id\": \"salad:generateSRT\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"segments\": {\n      \"@id\": \"salad:segments\",\n      \"@container\": \"@list\"\n    },\n    \"start\": {\n      \"@id\": \"salad:startTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"end\": {\n      \"@id\": \"salad:endTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"text\": {\n      \"@id\": \"schema:text\"\n    },\n    \"speaker\": {\n      \"@id\": \"salad:speaker\"\n    },\n    \"score\": {\n      \"@id\": \"salad:confidenceScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\"\n    },\n    \"srt_content\": {\n      \"@id\": \"salad:srtContent\"\n    },\n    \"create_time\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"update_time\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salad-transcription-api/refs/heads/main/json-ld/salad-transcription-api-context.jsonld
tags:
- Audio Transcription
- Captions
- Diarization
- GPU
- Speech Recognition
- Transcription
- Video Processing
- JSON-LD
- Linked Data
- Semantic Web
---
