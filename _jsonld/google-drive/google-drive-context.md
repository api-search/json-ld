---
api_specs:
- filename: google-drive-openapi.yml
  format: yaml
  label: Google Drive API v3
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/openapi/google-drive-openapi.yml
class_count: 18
classes:
- File
- id
- name
- mimeType
- parents
- createdTime
- modifiedTime
- size
- trashed
- starred
- shared
- webViewLink
- webContentLink
- iconLink
- owners
- Permission
- role
- emailAddress
context_file: json-ld/google-drive-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/json-ld/google-drive-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Drive from Google Drive.
layout: jsonld
name: Google Drive Context
namespaces:
- prefix: drive
  uri: https://developers.google.com/drive/api/v3/reference#
properties: []
property_count: 0
provider_name: Google Drive
provider_slug: google-drive
slug: google-drive-context
source_filename: google-drive-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"drive\": \"https://developers.google.com/drive/api/v3/reference#\",\n    \"File\": \"drive:File\",\n    \"id\": \"drive:fileId\",\n    \"name\": \"name\",\n    \"mimeType\": \"encodingFormat\",\n    \"parents\": \"isPartOf\",\n    \"createdTime\": \"dateCreated\",\n    \"modifiedTime\": \"dateModified\",\n    \"size\": \"contentSize\",\n    \"trashed\": \"drive:trashed\",\n    \"starred\": \"drive:starred\",\n    \"shared\": \"drive:shared\",\n    \"webViewLink\": \"url\",\n    \"webContentLink\": \"contentUrl\",\n    \"iconLink\": \"image\",\n    \"owners\": \"author\",\n    \"Permission\": \"drive:Permission\",\n    \"role\": \"drive:role\",\n    \"emailAddress\": \"email\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-drive/refs/heads/main/json-ld/google-drive-context.jsonld
tags:
- Cloud Storage
- Collaboration
- Document Management
- Drive
- Files
- Google
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
