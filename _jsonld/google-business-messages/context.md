---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Business Messages API
  slug: google-business-messages
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-business-messages/refs/heads/main/openapi/openapi.yml
class_count: 11
classes:
- Message
- sender
- recipient
- text
- dateCreated
- dateRead
- messageAttachment
- Organization
- Person
- name
- description
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-business-messages/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Business Messages.
layout: jsonld
name: context Context
namespaces:
- prefix: bm
  uri: https://businessmessages.googleapis.com/v1/
properties: []
property_count: 0
provider_name: Google Business Messages
provider_slug: google-business-messages
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bm\": \"https://businessmessages.googleapis.com/v1/\",\n    \"Message\": \"schema:Message\",\n    \"sender\": \"schema:sender\",\n    \"recipient\": \"schema:recipient\",\n    \"text\": \"schema:text\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateRead\": \"schema:dateRead\",\n    \"messageAttachment\": \"schema:messageAttachment\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-business-messages/refs/heads/main/json-ld/context.jsonld
tags:
- Business Communications
- Conversations
- Customer Support
- Google
- Messaging
- JSON-LD
- Linked Data
- Semantic Web
---
