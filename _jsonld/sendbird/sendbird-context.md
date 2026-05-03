---
api_specs:
- filename: sendbird-platform-openapi.yml
  format: yaml
  label: Sendbird Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sendbird/refs/heads/main/openapi/sendbird-platform-openapi.yml
class_count: 11
classes:
- user_id
- nickname
- metadata
- channel_url
- name
- message_id
- message
- type
- custom_type
- data
- mention_type
context_file: json-ld/sendbird-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sendbird/refs/heads/main/json-ld/sendbird-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sendbird from Sendbird.
layout: jsonld
name: Sendbird Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sendbird
  uri: https://sendbird.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: User
  type: reference
- container: ''
  name: GroupChannel
  type: reference
- container: ''
  name: Message
  type: reference
- container: ''
  name: profile_url
  type: reference
- container: ''
  name: is_online
  type: boolean
- container: ''
  name: is_active
  type: boolean
- container: ''
  name: created_at
  type: integer
- container: ''
  name: last_seen_at
  type: integer
- container: ''
  name: member_count
  type: integer
- container: ''
  name: cover_url
  type: reference
- container: ''
  name: is_distinct
  type: boolean
property_count: 11
provider_name: Sendbird
provider_slug: sendbird
slug: sendbird-context
source_filename: sendbird-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sendbird\": \"https://sendbird.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"User\": {\n      \"@id\": \"sendbird:User\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Person\"\n    },\n    \"GroupChannel\": {\n      \"@id\": \"sendbird:GroupChannel\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:ConversationThread\"\n    },\n    \"Message\": {\n      \"@id\": \"sendbird:Message\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Message\"\n    },\n\n    \"user_id\": \"@id\",\n    \"nickname\": \"schema:name\",\n    \"profile_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"is_online\": {\n      \"@id\": \"sendbird:isOnline\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_active\": {\n      \"@id\": \"sendbird:isActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"created_at\"\
  : {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"last_seen_at\": {\n      \"@id\": \"sendbird:lastSeenAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metadata\": \"sendbird:metadata\",\n\n    \"channel_url\": \"@id\",\n    \"name\": \"schema:name\",\n    \"member_count\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cover_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"is_distinct\": {\n      \"@id\": \"sendbird:isDistinct\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"message_id\": \"@id\",\n    \"message\": \"schema:text\",\n    \"type\": \"sendbird:messageType\",\n    \"custom_type\": \"sendbird:customType\",\n    \"data\": \"sendbird:customData\",\n    \"mention_type\": \"sendbird:mentionType\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sendbird/refs/heads/main/json-ld/sendbird-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
