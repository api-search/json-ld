---
class_count: 0
classes: []
context_file: json-ld/chat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/json-ld/chat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chat from Chat.
layout: jsonld
name: Chat Context
namespaces:
- prefix: chat
  uri: https://apievangelist.com/schemas/chat/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Conversation
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Participant
  type: ''
property_count: 3
provider_name: Chat
provider_slug: chat
slug: chat-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chat\": \"https://apievangelist.com/schemas/chat/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Conversation\": {\n      \"@id\": \"chat:Conversation\",\n      \"@context\": {\n        \"id\": \"chat:id\",\n        \"title\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"participantIds\": {\n          \"@id\": \"chat:participantIds\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"schema:Message\",\n      \"@context\": {\n        \"id\": \"chat:id\",\n        \"conversationId\": \"chat:conversationId\",\n        \"senderId\": {\n          \"@id\"\
  : \"schema:sender\",\n          \"@type\": \"@id\"\n        },\n        \"content\": \"schema:text\",\n        \"contentType\": \"chat:contentType\",\n        \"sentAt\": {\n          \"@id\": \"schema:dateSent\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"editedAt\": {\n          \"@id\": \"chat:editedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Participant\": {\n      \"@id\": \"chat:Participant\",\n      \"@context\": {\n        \"userId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"@id\"\n        },\n        \"role\": \"chat:role\",\n        \"joinedAt\": {\n          \"@id\": \"chat:joinedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/json-ld/chat-context.jsonld
tags:
- Chat
- Conversational AI
- Conversations
- Customer Support
- Messaging
- Real-time
- JSON-LD
- Linked Data
- Semantic Web
---
