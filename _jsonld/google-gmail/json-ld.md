---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Gmail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-gmail/refs/heads/main/openapi/openapi.yml
class_count: 6
classes:
- name
- description
- url
- provider
- dateCreated
- dateModified
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-gmail/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Gmail.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: gmail
  uri: https://gmail.googleapis.com/gmail/v1/
- prefix: goog
  uri: https://developers.google.com/workspace/gmail/api/reference/rest/v1/
properties:
- container: ''
  name: Message
  type: ''
- container: ''
  name: Label
  type: ''
- container: ''
  name: Thread
  type: ''
- container: ''
  name: Draft
  type: ''
- container: ''
  name: Profile
  type: ''
property_count: 5
provider_name: Google Gmail
provider_slug: google-gmail
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gmail\": \"https://gmail.googleapis.com/gmail/v1/\",\n    \"goog\": \"https://developers.google.com/workspace/gmail/api/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"Message\": {\n      \"@id\": \"goog:users.messages\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"threadId\": \"schema:isPartOf\",\n        \"snippet\": \"schema:abstract\",\n        \"labelIds\": \"schema:keywords\",\n        \"internalDate\": \"schema:dateCreated\",\n        \"sizeEstimate\": \"schema:contentSize\",\n        \"raw\": \"schema:encodingFormat\"\n      }\n    },\n    \"Label\": {\n      \"@id\": \"goog:users.labels\",\n      \"@context\": {\n        \"id\": \"schema:identifier\"\
  ,\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\"\n      }\n    },\n    \"Thread\": {\n      \"@id\": \"goog:users.threads\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"snippet\": \"schema:abstract\",\n        \"messages\": \"schema:hasPart\"\n      }\n    },\n    \"Draft\": {\n      \"@id\": \"goog:users.drafts\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"message\": \"schema:hasPart\"\n      }\n    },\n    \"Profile\": {\n      \"@id\": \"goog:users\",\n      \"@context\": {\n        \"emailAddress\": \"schema:email\",\n        \"messagesTotal\": \"schema:size\",\n        \"threadsTotal\": \"schema:size\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Gmail API\",\n  \"description\": \"The Gmail API lets you view and manage Gmail mailbox data like threads, messages, and labels.\",\n  \"url\": \"https://developers.google.com/workspace/gmail/api/guides\",\n  \"provider\"\
  : {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-gmail/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Drafts
- Email
- Gmail
- Google
- Google Workspace
- Labels
- Messaging
- Threads
- JSON-LD
- Linked Data
- Semantic Web
---
