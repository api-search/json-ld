---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Sideko API
  slug: sideko-api
  spec_type: OpenAPI
  url: https://docs.sideko.dev/reference/
class_count: 15
classes:
- ApiProject
- ApiVersion
- SdkGeneration
- DocSite
- MockServer
- ApiKey
- id
- name
- description
- slug
- version
- specFormat
- language
- status
- maskedKey
context_file: json-ld/sideko-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sideko/refs/heads/main/json-ld/sideko-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sideko from Sideko.
layout: jsonld
name: Sideko Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sideko
  uri: https://api.sideko.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: versionCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: endpoint
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: projectId
  type: reference
- container: ''
  name: versionId
  type: reference
property_count: 8
provider_name: Sideko
provider_slug: sideko
slug: sideko-context
source_filename: sideko-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sideko\": \"https://api.sideko.dev/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ApiProject\": \"sideko:ApiProject\",\n    \"ApiVersion\": \"sideko:ApiVersion\",\n    \"SdkGeneration\": \"sideko:SdkGeneration\",\n    \"DocSite\": \"sideko:DocSite\",\n    \"MockServer\": \"sideko:MockServer\",\n    \"ApiKey\": \"sideko:ApiKey\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"slug\": \"sideko:slug\",\n    \"versionCount\": {\n      \"@id\": \"sideko:versionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"version\": \"schema:version\",\n    \"specFormat\": \"sideko:specFormat\",\n \
  \   \"language\": \"sideko:programmingLanguage\",\n    \"status\": \"sideko:status\",\n    \"downloadUrl\": {\n      \"@id\": \"schema:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"endpoint\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"maskedKey\": \"sideko:maskedKey\",\n    \"projectId\": {\n      \"@id\": \"sideko:belongsToProject\",\n      \"@type\": \"@id\"\n    },\n    \"versionId\": {\n      \"@id\": \"sideko:basedOnVersion\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sideko/refs/heads/main/json-ld/sideko-context.jsonld
tags:
- CLI
- Documentation
- Mock Servers
- Platform
- SDKs
- API Tooling
- SDK Generation
- JSON-LD
- Linked Data
- Semantic Web
---
