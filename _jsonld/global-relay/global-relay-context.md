---
api_specs:
- filename: global-relay-conversation-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Conversation Archiving API
  slug: conversation-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-conversation-archiving-api-openapi.yml
- filename: global-relay-email-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Email Archiving API
  slug: email-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-email-archiving-api-openapi.yml
- filename: global-relay-voice-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Voice Archiving API
  slug: voice-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-voice-archiving-api-openapi.yml
- filename: global-relay-event-archiving-api-openapi.yml
  format: yaml
  label: Global Relay Event Archiving API
  slug: event-archiving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/openapi/global-relay-event-archiving-api-openapi.yml
class_count: 31
classes:
- Conversation
- conversationId
- channelType
- Participant
- participantId
- displayName
- email
- role
- Event
- eventType
- body
- fileIds
- referencedEventId
- Email
- messageId
- subject
- EmailAddress
- address
- VoiceRecord
- callId
- callType
- transcript
- EventCard
- cardId
- source
- Section
- sectionId
- File
- fileId
- fileName
- contentType
context_file: json-ld/global-relay-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/json-ld/global-relay-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Global Relay from Global Relay.
layout: jsonld
name: Global Relay Context
namespaces:
- prefix: gr
  uri: https://developers.globalrelay.com/schema/
properties:
- container: ''
  name: participants
  type: reference
- container: ''
  name: events
  type: reference
- container: ''
  name: timestamp
  type: schema:DateTime
- container: ''
  name: sender
  type: reference
- container: ''
  name: from
  type: reference
- container: ''
  name: to
  type: reference
- container: ''
  name: cc
  type: reference
- container: ''
  name: bcc
  type: reference
- container: ''
  name: sentDate
  type: schema:DateTime
- container: ''
  name: receivedDate
  type: schema:DateTime
- container: ''
  name: startTime
  type: schema:DateTime
- container: ''
  name: endTime
  type: schema:DateTime
- container: ''
  name: duration
  type: schema:Integer
- container: ''
  name: sections
  type: reference
- container: ''
  name: author
  type: reference
property_count: 15
provider_name: Global Relay
provider_slug: global-relay
slug: global-relay-context
source_filename: global-relay-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gr\": \"https://developers.globalrelay.com/schema/\",\n    \"Conversation\": \"gr:Conversation\",\n    \"conversationId\": \"gr:conversationId\",\n    \"channelType\": \"gr:channelType\",\n    \"participants\": {\n      \"@id\": \"gr:participants\",\n      \"@type\": \"@id\"\n    },\n    \"events\": {\n      \"@id\": \"gr:events\",\n      \"@type\": \"@id\"\n    },\n    \"Participant\": \"gr:Participant\",\n    \"participantId\": \"gr:participantId\",\n    \"displayName\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"role\": \"gr:role\",\n    \"Event\": \"gr:Event\",\n    \"eventType\": \"gr:eventType\",\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"sender\": {\n      \"@id\": \"gr:sender\",\n      \"@type\": \"@id\"\n    },\n    \"body\": \"schema:text\",\n    \"fileIds\": \"gr:fileIds\",\n    \"referencedEventId\": \"gr:referencedEventId\"\
  ,\n    \"Email\": \"schema:EmailMessage\",\n    \"messageId\": \"gr:messageId\",\n    \"from\": {\n      \"@id\": \"schema:sender\",\n      \"@type\": \"@id\"\n    },\n    \"to\": {\n      \"@id\": \"schema:recipient\",\n      \"@type\": \"@id\"\n    },\n    \"cc\": {\n      \"@id\": \"gr:ccRecipient\",\n      \"@type\": \"@id\"\n    },\n    \"bcc\": {\n      \"@id\": \"gr:bccRecipient\",\n      \"@type\": \"@id\"\n    },\n    \"subject\": \"schema:about\",\n    \"sentDate\": {\n      \"@id\": \"schema:dateSent\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"receivedDate\": {\n      \"@id\": \"schema:dateReceived\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"EmailAddress\": \"gr:EmailAddress\",\n    \"address\": \"schema:email\",\n    \"VoiceRecord\": \"gr:VoiceRecord\",\n    \"callId\": \"gr:callId\",\n    \"callType\": \"gr:callType\",\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"endTime\": {\n    \
  \  \"@id\": \"schema:endDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"transcript\": \"gr:transcript\",\n    \"EventCard\": \"gr:EventCard\",\n    \"cardId\": \"gr:cardId\",\n    \"source\": \"gr:source\",\n    \"sections\": {\n      \"@id\": \"gr:sections\",\n      \"@type\": \"@id\"\n    },\n    \"Section\": \"gr:Section\",\n    \"sectionId\": \"gr:sectionId\",\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"File\": \"schema:MediaObject\",\n    \"fileId\": \"gr:fileId\",\n    \"fileName\": \"schema:name\",\n    \"contentType\": \"schema:encodingFormat\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/global-relay/refs/heads/main/json-ld/global-relay-context.jsonld
tags:
- Archiving
- Compliance
- Data Retention
- Email Security
- Regulatory Compliance
- JSON-LD
- Linked Data
- Semantic Web
---
