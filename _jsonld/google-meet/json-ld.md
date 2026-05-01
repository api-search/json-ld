---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Meet API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Meet.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: meet
  uri: https://meet.googleapis.com/v2/
- prefix: goog
  uri: https://developers.google.com/workspace/meet/api/reference/rest/v2/
properties:
- container: ''
  name: Space
  type: ''
- container: ''
  name: ConferenceRecord
  type: ''
- container: ''
  name: Participant
  type: ''
- container: ''
  name: Recording
  type: ''
- container: ''
  name: Transcript
  type: ''
- container: ''
  name: TranscriptEntry
  type: ''
property_count: 6
provider_name: Google Meet
provider_slug: google-meet
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"meet\": \"https://meet.googleapis.com/v2/\",\n    \"goog\": \"https://developers.google.com/workspace/meet/api/reference/rest/v2/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Space\": {\n      \"@id\": \"goog:spaces\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"meetingUri\": \"schema:url\",\n        \"meetingCode\": \"schema:accessCode\",\n        \"config\": \"schema:accessMode\"\n      }\n    },\n    \"ConferenceRecord\": {\n      \"@id\": \"goog:conferenceRecords\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"startTime\": \"schema:startDate\",\n        \"endTime\": \"schema:endDate\",\n        \"expireTime\": \"schema:expires\",\n        \"space\": \"schema:location\"\n      }\n    },\n    \"Participant\": {\n      \"@id\": \"\
  goog:conferenceRecords.participants\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"earliestStartTime\": \"schema:startDate\",\n        \"latestEndTime\": \"schema:endDate\"\n      }\n    },\n    \"Recording\": {\n      \"@id\": \"goog:conferenceRecords.recordings\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"state\": \"schema:creativeWorkStatus\",\n        \"startTime\": \"schema:startDate\",\n        \"endTime\": \"schema:endDate\"\n      }\n    },\n    \"Transcript\": {\n      \"@id\": \"goog:conferenceRecords.transcripts\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"state\": \"schema:creativeWorkStatus\",\n        \"startTime\": \"schema:startDate\",\n        \"endTime\": \"schema:endDate\"\n      }\n    },\n    \"TranscriptEntry\": {\n      \"@id\": \"goog:conferenceRecords.transcripts.entries\",\n      \"@context\": {\n        \"participant\": \"schema:agent\",\n        \"text\": \"schema:text\"\
  ,\n        \"languageCode\": \"schema:inLanguage\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Meet API\",\n  \"description\": \"The Google Meet REST API enables creating and managing meeting spaces, conference records, recordings, and transcripts.\",\n  \"url\": \"https://developers.google.com/workspace/meet/api/guides/overview\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-meet/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Google
- Google Workspace
- Meetings
- Recordings
- Transcripts
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
