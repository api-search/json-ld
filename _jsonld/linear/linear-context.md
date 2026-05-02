---
api_specs:
- filename: linear-graphql-openapi.yml
  format: yaml
  label: Linear GraphQL API
  slug: linear-graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/openapi/linear-graphql-openapi.yml
- filename: linear-webhooks-asyncapi.yml
  format: yaml
  label: Linear Webhooks API
  slug: linear-webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/asyncapi/linear-webhooks-asyncapi.yml
class_count: 17
classes:
- Issue
- id
- title
- description
- url
- assignee
- creator
- User
- name
- email
- avatarUrl
- Team
- Project
- Cycle
- IssueLabel
- color
- state
context_file: json-ld/linear-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-ld/linear-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Linear from linear.
layout: jsonld
name: Linear Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: linear
  uri: https://linear.app/developers/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: dueDate
  type: date
- container: ''
  name: startsAt
  type: dateTime
- container: ''
  name: endsAt
  type: dateTime
- container: ''
  name: priority
  type: integer
- container: ''
  name: estimate
  type: decimal
- container: set
  name: labels
  type: ''
- container: ''
  name: identifier
  type: ''
- container: ''
  name: branchName
  type: ''
property_count: 11
provider_name: linear
provider_slug: linear
slug: linear-context
source_filename: linear-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"linear\": \"https://linear.app/developers/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Issue\": \"schema:SoftwareApplication\",\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n    \"assignee\": \"schema:contributor\",\n    \"creator\": \"schema:author\",\n    \"User\": \"schema:Person\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"avatarUrl\": \"schema:image\"\
  ,\n    \"Team\": \"schema:Organization\",\n    \"Project\": \"schema:Project\",\n    \"Cycle\": \"schema:Event\",\n    \"startsAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endsAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"IssueLabel\": \"schema:DefinedTerm\",\n    \"color\": \"schema:color\",\n    \"priority\": {\n      \"@id\": \"linear:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimate\": {\n      \"@id\": \"linear:estimate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"state\": \"schema:status\",\n    \"labels\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"identifier\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"branchName\": {\n      \"@id\": \"linear:branchName\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/linear/refs/heads/main/json-ld/linear-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
