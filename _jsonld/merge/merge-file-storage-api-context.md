---
api_specs:
- filename: merge-hris-api-openapi.yaml
  format: yaml
  label: Merge HRIS API
  slug: hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-hris-api-openapi.yaml
- filename: merge-ats-api-openapi.yaml
  format: yaml
  label: Merge ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ats-api-openapi.yaml
- filename: merge-accounting-api-openapi.yaml
  format: yaml
  label: Merge Accounting API
  slug: accounting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-accounting-api-openapi.yaml
- filename: merge-ticketing-api-openapi.yaml
  format: yaml
  label: Merge Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-ticketing-api-openapi.yaml
- filename: merge-crm-api-openapi.yaml
  format: yaml
  label: Merge CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-crm-api-openapi.yaml
- filename: merge-file-storage-api-openapi.yaml
  format: yaml
  label: Merge File Storage API
  slug: file-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/openapi/merge-file-storage-api-openapi.yaml
class_count: 5
classes:
- File
- Folder
- Drive
- FSGroup
- FSUser
context_file: json-ld/merge-file-storage-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-file-storage-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge File Storage Api from Merge.
layout: jsonld
name: Merge File Storage Api Context
namespaces:
- prefix: merge
  uri: https://api.merge.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: fileUrl
  type: reference
- container: ''
  name: fileThumbnailUrl
  type: reference
- container: ''
  name: size
  type: integer
- container: ''
  name: mimeType
  type: string
- container: ''
  name: folder
  type: reference
- container: ''
  name: drive
  type: reference
- container: ''
  name: folderUrl
  type: reference
- container: ''
  name: parentFolder
  type: reference
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: isMe
  type: boolean
- container: set
  name: users
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: remoteWasDeleted
  type: boolean
property_count: 17
provider_name: Merge
provider_slug: merge
slug: merge-file-storage-api-context
source_filename: merge-file-storage-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"File\": \"merge:File\",\n    \"Folder\": \"merge:Folder\",\n    \"Drive\": \"merge:Drive\",\n    \"FSGroup\": \"merge:FSGroup\",\n    \"FSUser\": \"merge:FSUser\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"fileUrl\": { \"@id\": \"schema:contentUrl\", \"@type\": \"@id\" },\n    \"fileThumbnailUrl\": { \"@id\": \"schema:thumbnailUrl\", \"@type\": \"@id\" },\n    \"size\": { \"@id\": \"schema:contentSize\", \"@type\": \"xsd:integer\" },\n    \"mimeType\": { \"@id\": \"schema:encodingFormat\", \"@type\": \"xsd:string\" },\n    \"folder\"\
  : { \"@id\": \"merge:folder\", \"@type\": \"@id\" },\n    \"drive\": { \"@id\": \"merge:drive\", \"@type\": \"@id\" },\n    \"folderUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"parentFolder\": { \"@id\": \"merge:parent_folder\", \"@type\": \"@id\" },\n    \"emailAddress\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"isMe\": { \"@id\": \"merge:is_me\", \"@type\": \"xsd:boolean\" },\n    \"users\": { \"@id\": \"merge:users\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-file-storage-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
