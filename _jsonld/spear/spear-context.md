---
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/spear-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spear/refs/heads/main/json-ld/spear-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spear from Spear.
layout: jsonld
name: Spear Context
namespaces:
- prefix: spear
  uri: https://spear.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Workspace
  type: reference
- container: ''
  name: Collection
  type: reference
- container: ''
  name: Project
  type: reference
- container: ''
  name: Member
  type: reference
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 10
provider_name: Spear
provider_slug: spear
slug: spear-context
source_filename: spear-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spear\": \"https://spear.dev/vocab/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"Workspace\": {\n      \"@id\": \"spear:Workspace\",\n      \"@type\": \"@id\"\n    },\n    \"Collection\": {\n      \"@id\": \"spear:Collection\",\n      \"@type\": \"@id\"\n    },\n    \"Project\": {\n      \"@id\": \"spear:Project\",\n      \"@type\": \"@id\"\n    },\n    \"Member\": {\n      \"@id\": \"spear:Member\",\n      \"@type\": \"@id\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"spear:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"spear:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"spear:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"spear:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"spear:createdAt\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"spear:modifiedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spear/refs/heads/main/json-ld/spear-context.jsonld
tags:
- API Development
- Collaboration
- Developer Tools
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
