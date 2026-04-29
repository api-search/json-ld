---
api_specs:
- filename: microsoft-word-graph-api.yaml
  format: yaml
  label: Microsoft Graph Word API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-graph-api.yaml
- filename: microsoft-word-javascript-api.yaml
  format: yaml
  label: Office JavaScript API for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-javascript-api.yaml
- filename: microsoft-word-open-xml-sdk.yaml
  format: yaml
  label: Open XML SDK for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-open-xml-sdk.yaml
class_count: 11
classes:
- DriveItem
- Permission
- IdentitySet
- ItemReference
- FileFacet
- FolderFacet
- DriveItemVersion
- ThumbnailSet
- UploadSession
- name
- description
context_file: json-ld/microsoft-word-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Word Graph Api from Microsoft Word.
layout: jsonld
name: Microsoft Word Graph Api Context
namespaces:
- prefix: msword
  uri: https://developer.microsoft.com/schema/word/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: webUrl
  type: reference
- container: ''
  name: webDavUrl
  type: reference
- container: ''
  name: createdDateTime
  type: dateTime
- container: ''
  name: lastModifiedDateTime
  type: dateTime
- container: ''
  name: size
  type: integer
- container: ''
  name: eTag
  type: string
- container: ''
  name: cTag
  type: string
- container: ''
  name: mimeType
  type: string
- container: ''
  name: childCount
  type: integer
- container: set
  name: roles
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: driveId
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: uploadUrl
  type: reference
- container: ''
  name: expirationDateTime
  type: dateTime
property_count: 16
provider_name: Microsoft Word
provider_slug: microsoft-word
slug: microsoft-word-graph-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"msword\": \"https://developer.microsoft.com/schema/word/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"DriveItem\": \"msword:DriveItem\",\n    \"Permission\": \"msword:Permission\",\n    \"IdentitySet\": \"msword:IdentitySet\",\n    \"ItemReference\": \"msword:ItemReference\",\n    \"FileFacet\": \"msword:FileFacet\",\n    \"FolderFacet\": \"msword:FolderFacet\",\n    \"DriveItemVersion\": \"msword:DriveItemVersion\",\n    \"ThumbnailSet\": \"msword:ThumbnailSet\",\n    \"UploadSession\": \"msword:UploadSession\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"webUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"webDavUrl\": {\n      \"@id\": \"msword:web_dav_url\",\n      \"@type\": \"@id\"\n    },\n    \"createdDateTime\": {\n      \"@id\": \"\
  schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedDateTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eTag\": {\n      \"@id\": \"msword:e_tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cTag\": {\n      \"@id\": \"msword:c_tag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mimeType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childCount\": {\n      \"@id\": \"msword:child_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"roles\": {\n      \"@id\": \"msword:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"driveId\": {\n      \"@id\": \"msword:drive_id\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"path\": {\n      \"@id\": \"msword:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"msword:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadUrl\": {\n      \"@id\": \"msword:upload_url\",\n      \"@type\": \"@id\"\n    },\n    \"expirationDateTime\": {\n      \"@id\": \"msword:expiration_date_time\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/json-ld/microsoft-word-graph-api-context.jsonld
tags:
- Documents
- Microsoft 365
- Office
- Productivity
- Word Processing
- JSON-LD
- Linked Data
- Semantic Web
---
