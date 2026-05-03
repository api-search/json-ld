---
api_specs:
- filename: seismic-content-openapi.yml
  format: yaml
  label: Seismic Content API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-content-openapi.yml
- filename: seismic-livedocs-openapi.yml
  format: yaml
  label: Seismic LiveDocs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-livedocs-openapi.yml
- filename: seismic-analytics-openapi.yml
  format: yaml
  label: Seismic Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-analytics-openapi.yml
- filename: seismic-user-management-openapi.yml
  format: yaml
  label: Seismic User Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/openapi/seismic-user-management-openapi.yml
class_count: 13
classes:
- id
- name
- description
- fileType
- mimeType
- status
- tags
- email
- firstName
- lastName
- displayName
- outputFormat
- inputs
context_file: json-ld/seismic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/json-ld/seismic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Seismic from Seismic.
layout: jsonld
name: Seismic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: seismic
  uri: https://developer.seismic.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ContentItem
  type: reference
- container: ''
  name: ContentFolder
  type: reference
- container: ''
  name: ContentProfile
  type: reference
- container: ''
  name: LiveDocTemplate
  type: reference
- container: ''
  name: GenerationJob
  type: reference
- container: ''
  name: User
  type: reference
- container: ''
  name: Group
  type: reference
- container: ''
  name: Role
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: thumbnailUrl
  type: reference
- container: ''
  name: versionNumber
  type: integer
- container: ''
  name: folderId
  type: reference
- container: ''
  name: contentProfileId
  type: reference
- container: ''
  name: createdBy
  type: reference
- container: ''
  name: modifiedBy
  type: reference
- container: ''
  name: templateId
  type: reference
- container: ''
  name: contentId
  type: reference
- container: ''
  name: views
  type: integer
- container: ''
  name: downloads
  type: integer
- container: ''
  name: shares
  type: integer
- container: ''
  name: engagementScore
  type: float
property_count: 23
provider_name: Seismic
provider_slug: seismic
slug: seismic-context
source_filename: seismic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"seismic\": \"https://developer.seismic.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ContentItem\": {\n      \"@id\": \"seismic:ContentItem\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:DigitalDocument\"\n    },\n    \"ContentFolder\": {\n      \"@id\": \"seismic:ContentFolder\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Collection\"\n    },\n    \"ContentProfile\": {\n      \"@id\": \"seismic:ContentProfile\",\n      \"@type\": \"@id\"\n    },\n    \"LiveDocTemplate\": {\n      \"@id\": \"seismic:LiveDocTemplate\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:CreativeWork\"\n    },\n    \"GenerationJob\": {\n      \"@id\": \"seismic:GenerationJob\",\n      \"@type\": \"@id\"\n    },\n    \"User\": {\n      \"@id\": \"seismic:User\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Person\"\n   \
  \ },\n    \"Group\": {\n      \"@id\": \"seismic:Group\",\n      \"@type\": \"@id\",\n      \"subClassOf\": \"schema:Organization\"\n    },\n    \"Role\": {\n      \"@id\": \"seismic:Role\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fileType\": \"seismic:fileType\",\n    \"fileSize\": {\n      \"@id\": \"schema:fileSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mimeType\": \"schema:encodingFormat\",\n    \"status\": \"seismic:publicationStatus\",\n    \"tags\": \"schema:keywords\",\n    \"thumbnailUrl\": {\n      \"@id\": \"schema:thumbnailUrl\",\n      \"@type\": \"@id\"\n    },\n    \"versionNumber\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"folderId\": {\n      \"@id\": \"seismic:containedInFolder\",\n      \"@type\": \"@id\"\n    },\n    \"contentProfileId\": {\n      \"@id\": \"seismic:hasContentProfile\",\n      \"@type\": \"@id\"\n    },\n    \"createdBy\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"modifiedBy\": {\n      \"@id\": \"schema:editor\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"displayName\": \"schema:name\",\n    \"templateId\": {\n      \"@id\": \"seismic:usesTemplate\",\n      \"@type\": \"@id\"\n    },\n    \"outputFormat\": \"seismic:outputFormat\",\n    \"inputs\": \"seismic:templateInputs\",\n    \"contentId\": {\n      \"@id\": \"seismic:refersToContent\",\n      \"@type\": \"@id\"\n    },\n    \"views\": {\n      \"@id\": \"schema:interactionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"downloads\": {\n      \"@id\": \"\
  seismic:downloadCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shares\": {\n      \"@id\": \"seismic:shareCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"engagementScore\": {\n      \"@id\": \"seismic:engagementScore\",\n      \"@type\": \"xsd:float\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/seismic/refs/heads/main/json-ld/seismic-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
