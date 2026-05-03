---
api_specs:
- filename: retool-management-api-openapi.yml
  format: yaml
  label: Retool Management API
  slug: retool-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/openapi/retool-management-api-openapi.yml
class_count: 13
classes:
- id
- type
- User
- Group
- App
- Resource
- Folder
- email
- firstName
- lastName
- name
- description
- displayName
context_file: json-ld/retool-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/json-ld/retool-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Retool from Retool.
layout: jsonld
name: Retool Context
namespaces:
- prefix: retool
  uri: https://retool.com/ns/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: isAdmin
  type: boolean
- container: ''
  name: isDisabled
  type: boolean
- container: ''
  name: userType
  type: string
- container: set
  name: groups
  type: ''
- container: set
  name: members
  type: ''
- container: ''
  name: folderId
  type: reference
- container: ''
  name: createdBy
  type: reference
- container: set
  name: resources
  type: ''
- container: ''
  name: resourceType
  type: string
- container: ''
  name: folderType
  type: string
- container: ''
  name: parentFolderId
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 13
provider_name: Retool
provider_slug: retool
slug: retool-context
source_filename: retool-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"retool\": \"https://retool.com/ns/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"User\": \"schema:Person\",\n    \"Group\": \"schema:Organization\",\n    \"App\": \"schema:SoftwareApplication\",\n    \"Resource\": \"schema:Dataset\",\n    \"Folder\": \"retool:Folder\",\n\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"isAdmin\": {\n      \"@id\": \"retool:isAdmin\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDisabled\": {\n      \"@id\": \"retool:isDisabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"userType\": {\n      \"@id\": \"retool:userType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"schema:memberOf\",\n      \"@container\": \"@set\"\n    },\n\n    \"name\"\
  : \"schema:name\",\n    \"description\": \"schema:description\",\n    \"members\": {\n      \"@id\": \"schema:member\",\n      \"@container\": \"@set\"\n    },\n\n    \"folderId\": {\n      \"@id\": \"retool:folder\",\n      \"@type\": \"@id\"\n    },\n    \"createdBy\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"resources\": {\n      \"@id\": \"retool:usesResource\",\n      \"@container\": \"@set\"\n    },\n\n    \"resourceType\": {\n      \"@id\": \"retool:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": \"schema:alternateName\",\n\n    \"folderType\": {\n      \"@id\": \"retool:folderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentFolderId\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/json-ld/retool-context.jsonld
tags:
- Admin Panel
- Dashboard
- Internal Tools
- Low Code
- No Code
- JSON-LD
- Linked Data
- Semantic Web
---
