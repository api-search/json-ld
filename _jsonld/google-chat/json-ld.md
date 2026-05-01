---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Chat API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-chat/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-chat/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Chat.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: chat
  uri: https://chat.googleapis.com/v1/
- prefix: goog
  uri: https://developers.google.com/workspace/chat/api/reference/rest/v1/
properties:
- container: ''
  name: Space
  type: ''
- container: ''
  name: Membership
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: Reaction
  type: ''
property_count: 4
provider_name: Google Chat
provider_slug: google-chat
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"chat\": \"https://chat.googleapis.com/v1/\",\n    \"goog\": \"https://developers.google.com/workspace/chat/api/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Space\": {\n      \"@id\": \"goog:spaces\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"displayName\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"spaceType\": \"schema:additionalType\"\n      }\n    },\n    \"Membership\": {\n      \"@id\": \"goog:spaces.members\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"state\": \"schema:status\",\n        \"role\": \"schema:roleName\",\n        \"member\": \"schema:member\",\n        \"createTime\": \"schema:dateCreated\"\n      }\n    },\n    \"Message\": {\n      \"@id\": \"goog:spaces.messages\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"sender\": \"schema:author\",\n        \"createTime\": \"schema:dateCreated\",\n        \"text\": \"schema:text\",\n        \"thread\": \"schema:isPartOf\",\n        \"space\": \"schema:spatial\"\n      }\n    },\n    \"Reaction\": {\n      \"@id\": \"goog:spaces.messages.reactions\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"user\": \"schema:agent\",\n        \"emoji\": \"schema:character\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Chat API\",\n  \"description\": \"The Google Chat API enables building Chat apps for managing spaces, memberships, messages, reactions, and custom emojis.\",\n  \"url\": \"https://developers.google.com/workspace/chat/api/guides\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-chat/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Chat
- Collaboration
- Google
- Google Workspace
- Messaging
- Spaces
- JSON-LD
- Linked Data
- Semantic Web
---
