---
api_specs:
- filename: zoom-api.yaml
  format: yaml
  label: Zoom API
  slug: zoom-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/zoom/api/master/openapi/zoom-api.yaml
class_count: 0
classes: []
context_file: json-ld/visioconference-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/visioconference/refs/heads/main/json-ld/visioconference-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Visioconference from Visioconference.
layout: jsonld
name: Visioconference Context
namespaces:
- prefix: vc
  uri: https://api-evangelist.github.io/visioconference/vocab/
- prefix: webrtc
  uri: https://www.w3.org/TR/webrtc/
properties:
- container: ''
  name: VideoConferenceMeeting
  type: reference
- container: ''
  name: Participant
  type: reference
- container: ''
  name: Recording
  type: reference
- container: ''
  name: Room
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: topic
  type: ''
- container: ''
  name: agenda
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: startTime
  type: http://www.w3.org/2001/XMLSchema#dateTime
- container: ''
  name: endTime
  type: http://www.w3.org/2001/XMLSchema#dateTime
- container: ''
  name: duration
  type: ''
- container: ''
  name: timezone
  type: ''
- container: ''
  name: joinUrl
  type: ''
- container: ''
  name: hostId
  type: ''
- container: ''
  name: hostEmail
  type: ''
- container: list
  name: participants
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: role
  type: ''
- container: ''
  name: joinTime
  type: ''
- container: ''
  name: leaveTime
  type: ''
- container: ''
  name: recording
  type: ''
- container: ''
  name: downloadUrl
  type: ''
- container: ''
  name: fileSize
  type: ''
- container: ''
  name: maxParticipants
  type: ''
- container: ''
  name: waitingRoom
  type: ''
- container: ''
  name: password
  type: ''
property_count: 27
provider_name: Visioconference
provider_slug: visioconference
slug: visioconference-context
source_filename: visioconference-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vc\": \"https://api-evangelist.github.io/visioconference/vocab/\",\n    \"webrtc\": \"https://www.w3.org/TR/webrtc/\",\n\n    \"VideoConferenceMeeting\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"Participant\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"Recording\": {\n      \"@id\": \"schema:VideoObject\",\n      \"@type\": \"@id\"\n    },\n    \"Room\": {\n      \"@id\": \"https://api-evangelist.github.io/visioconference/vocab/Room\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"topic\": {\n      \"@id\": \"schema:name\"\n    },\n    \"agenda\": {\n      \"@id\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"schema:eventStatus\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\
  \n    },\n    \"endTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\"\n    },\n    \"timezone\": {\n      \"@id\": \"https://api-evangelist.github.io/visioconference/vocab/timezone\"\n    },\n    \"joinUrl\": {\n      \"@id\": \"schema:url\"\n    },\n    \"hostId\": {\n      \"@id\": \"schema:organizer\"\n    },\n    \"hostEmail\": {\n      \"@id\": \"schema:organizer\"\n    },\n    \"participants\": {\n      \"@id\": \"schema:attendee\",\n      \"@container\": \"@list\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\"\n    },\n    \"joinTime\": {\n      \"@id\": \"schema:startDate\"\n    },\n    \"leaveTime\": {\n      \"@id\": \"schema:endDate\"\n    },\n    \"recording\": {\n      \"@id\": \"schema:recordedIn\"\n    },\n    \"downloadUrl\"\
  : {\n      \"@id\": \"schema:contentUrl\"\n    },\n    \"fileSize\": {\n      \"@id\": \"schema:fileSize\"\n    },\n    \"maxParticipants\": {\n      \"@id\": \"schema:maximumAttendeeCapacity\"\n    },\n    \"waitingRoom\": {\n      \"@id\": \"https://api-evangelist.github.io/visioconference/vocab/waitingRoom\"\n    },\n    \"password\": {\n      \"@id\": \"https://api-evangelist.github.io/visioconference/vocab/password\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/visioconference/refs/heads/main/json-ld/visioconference-context.jsonld
tags:
- Audio
- Chat
- Collaboration
- Communication
- Conferencing
- Live Streaming
- Real-Time
- Remote Work
- Screen Sharing
- Video
- WebRTC
- JSON-LD
- Linked Data
- Semantic Web
---
