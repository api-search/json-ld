---
api_specs:
- filename: dead-drop-openapi.yml
  format: yaml
  label: Dead Drop API v1
  slug: dead-drop-api-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dead-drop/refs/heads/main/openapi/dead-drop-openapi.yml
class_count: 18
classes:
- Drop
- DropVersion
- id
- name
- description
- tier
- visibility
- payload
- salt
- iv
- encryptionAlgo
- encryptionParams
- mimeType
- hashAlgo
- contentHash
- version
- versions
- available
context_file: json-ld/dead-drop-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dead-drop/refs/heads/main/json-ld/dead-drop-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dead Drop from Dead Drop.
layout: jsonld
name: Dead Drop Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: dd
  uri: https://raw.githubusercontent.com/api-evangelist/dead-drop/main/json-ld/dead-drop-context.jsonld#
properties:
- container: ''
  name: expiresAt
  type: schema:DateTime
- container: ''
  name: createdAt
  type: schema:DateTime
property_count: 2
provider_name: Dead Drop
provider_slug: dead-drop
slug: dead-drop-context
source_filename: dead-drop-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"dd\": \"https://raw.githubusercontent.com/api-evangelist/dead-drop/main/json-ld/dead-drop-context.jsonld#\",\n    \"Drop\": \"dd:Drop\",\n    \"DropVersion\": \"dd:DropVersion\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"tier\": \"dd:tier\",\n    \"visibility\": \"dd:visibility\",\n    \"payload\": \"dd:payload\",\n    \"salt\": \"dd:salt\",\n    \"iv\": \"dd:iv\",\n    \"encryptionAlgo\": \"sec:cipherAlgorithm\",\n    \"encryptionParams\": \"dd:encryptionParams\",\n    \"mimeType\": \"schema:encodingFormat\",\n    \"hashAlgo\": \"sec:digestAlgorithm\",\n    \"contentHash\": \"sec:digestValue\",\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\"\
  : \"schema:DateTime\"\n    },\n    \"version\": \"schema:version\",\n    \"versions\": \"dd:versions\",\n    \"available\": \"dd:available\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dead-drop/refs/heads/main/json-ld/dead-drop-context.jsonld
tags:
- Messaging
- Privacy
- Anonymous
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
