---
api_specs:
- filename: bitbucket-cloud-rest-api-openapi.json
  format: json
  label: Bitbucket Cloud REST API
  slug: bitbucket-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/openapi/bitbucket-cloud-rest-api-openapi.json
class_count: 4
classes:
- Repository
- Pullrequest
- Pipeline
- Commit
context_file: json-ld/bitbucket-cloud-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/json-ld/bitbucket-cloud-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bitbucket Cloud Rest Api from Bitbucket.
layout: jsonld
name: Bitbucket Cloud Rest Api Context
namespaces:
- prefix: bb
  uri: https://api.bitbucket.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: updatedOn
  type: dateTime
- container: ''
  name: completedOn
  type: dateTime
- container: ''
  name: size
  type: integer
- container: ''
  name: language
  type: string
- container: ''
  name: hash
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: buildNumber
  type: integer
- container: ''
  name: commentCount
  type: integer
- container: ''
  name: taskCount
  type: integer
- container: ''
  name: forkPolicy
  type: string
- container: ''
  name: scm
  type: string
- container: set
  name: reviewers
  type: reference
- container: set
  name: participants
  type: reference
- container: set
  name: parents
  type: reference
property_count: 23
provider_name: Bitbucket
provider_slug: bitbucket
slug: bitbucket-cloud-rest-api-context
source_filename: bitbucket-cloud-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://api.bitbucket.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Repository\": \"bb:Repository\",\n    \"Pullrequest\": \"bb:Pullrequest\",\n    \"Pipeline\": \"bb:Pipeline\",\n    \"Commit\": \"bb:Commit\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"bb:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"bb:full_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"bb:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPrivate\": {\n      \"@id\": \"bb:is_private\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdOn\": {\n      \"\
  @id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedOn\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedOn\": {\n      \"@id\": \"bb:completed_on\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"size\": {\n      \"@id\": \"bb:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"language\": {\n      \"@id\": \"bb:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hash\": {\n      \"@id\": \"bb:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"bb:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"bb:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildNumber\": {\n      \"@id\": \"bb:build_number\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commentCount\": {\n      \"@id\": \"bb:comment_count\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"taskCount\": {\n      \"@id\": \"bb:task_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"forkPolicy\": {\n      \"@id\": \"bb:fork_policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scm\": {\n      \"@id\": \"bb:scm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewers\": {\n      \"@id\": \"bb:reviewers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"participants\": {\n      \"@id\": \"bb:participants\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"parents\": {\n      \"@id\": \"bb:parents\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/json-ld/bitbucket-cloud-rest-api-context.jsonld
tags:
- Atlassian
- CI/CD
- Code Collaboration
- Code Review
- DevOps
- Git
- Pull Requests
- Repository Hosting
- Version Control
- JSON-LD
- Linked Data
- Semantic Web
---
