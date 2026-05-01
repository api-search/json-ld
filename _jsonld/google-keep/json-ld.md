---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Keep API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Keep.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: keep
  uri: https://keep.googleapis.com/v1/
- prefix: goog
  uri: https://developers.google.com/workspace/keep/api/reference/rest/v1/
properties:
- container: ''
  name: Note
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: Attachment
  type: ''
property_count: 3
provider_name: Google Keep
provider_slug: google-keep
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"keep\": \"https://keep.googleapis.com/v1/\",\n    \"goog\": \"https://developers.google.com/workspace/keep/api/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"Note\": {\n      \"@id\": \"goog:notes\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"createTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\",\n        \"trashed\": \"schema:deleted\",\n        \"body\": \"schema:text\",\n        \"permissions\": \"schema:hasDigitalDocumentPermission\",\n        \"attachments\": \"schema:associatedMedia\"\n      }\n    },\n    \"Permission\": {\n      \"@id\": \"goog:notes.permissions\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n\
  \        \"role\": \"schema:roleName\"\n      }\n    },\n    \"Attachment\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@context\": {\n        \"name\": \"schema:identifier\",\n        \"mimeType\": \"schema:encodingFormat\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"Google Keep API\",\n  \"description\": \"The Google Keep API enables enterprise administrators to manage notes, attachments, and permissions.\",\n  \"url\": \"https://developers.google.com/workspace/keep/api/guides\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-keep/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Google
- Google Workspace
- Notes
- Organization
- Productivity
- JSON-LD
- Linked Data
- Semantic Web
---
