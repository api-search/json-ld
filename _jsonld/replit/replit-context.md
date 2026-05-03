---
api_specs:
- filename: replit-openapi.yml
  format: yaml
  label: Replit
  slug: replit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/openapi/replit-openapi.yml
class_count: 1
classes:
- id
context_file: json-ld/replit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/json-ld/replit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Replit from Replit.
layout: jsonld
name: Replit Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: replit
  uri: https://replit.com/api/v1#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Repl
  type: schema:SoftwareSourceCode
- container: ''
  name: User
  type: schema:Person
- container: ''
  name: Deployment
  type: schema:WebApplication
- container: ''
  name: slug
  type: string
- container: ''
  name: title
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: language
  type: ''
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: url
  type: anyURI
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: owner
  type: schema:Person
- container: ''
  name: username
  type: ''
- container: ''
  name: displayName
  type: ''
- container: ''
  name: isVerified
  type: boolean
- container: ''
  name: deploymentId
  type: ''
- container: ''
  name: replId
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: domain
  type: anyURI
property_count: 19
provider_name: Replit
provider_slug: replit
slug: replit-context
source_filename: replit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"replit\": \"https://replit.com/api/v1#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Repl\": {\n      \"@id\": \"replit:Repl\",\n      \"@type\": \"schema:SoftwareSourceCode\"\n    },\n    \"User\": {\n      \"@id\": \"replit:User\",\n      \"@type\": \"schema:Person\"\n    },\n    \"Deployment\": {\n      \"@id\": \"replit:Deployment\",\n      \"@type\": \"schema:WebApplication\"\n    },\n\n    \"id\": \"@id\",\n    \"slug\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"language\": {\n      \"@id\": \"schema:programmingLanguage\"\n    },\n    \"isPrivate\": {\n      \"@id\": \"schema:accessMode\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\"\
  : \"xsd:anyURI\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"schema:Person\"\n    },\n    \"username\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"isVerified\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deploymentId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"replId\": {\n      \"@id\": \"replit:replId\"\n    },\n    \"status\": {\n      \"@id\": \"schema:actionStatus\"\n    },\n    \"domain\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/json-ld/replit-context.jsonld
tags:
- Code
- Compiling
- Development Environment
- Programming Languages
- Version Control
- JSON-LD
- Linked Data
- Semantic Web
---
