---
api_specs:
- filename: unkey-openapi.yml
  format: yaml
  label: Unkey API
  slug: unkey-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/openapi/unkey-openapi.yml
class_count: 10
classes:
- APIKey
- APINamespace
- Identity
- RateLimit
- Permission
- Role
- Workspace
- id
- name
- description
context_file: json-ld/unkey-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-ld/unkey-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unkey from Unkey.
layout: jsonld
name: Unkey Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: unkey
  uri: https://unkey.com/ontology#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: createdAt
  type: long
- container: ''
  name: updatedAt
  type: long
- container: ''
  name: expires
  type: long
- container: ''
  name: apiId
  type: string
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: externalId
  type: string
- container: ''
  name: identityId
  type: string
- container: ''
  name: meta
  type: '@json'
- container: set
  name: roles
  type: ''
- container: set
  name: permissions
  type: ''
- container: ''
  name: hash
  type: string
- container: ''
  name: ratelimit
  type: unkey:RateLimit
- container: ''
  name: limit
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: remaining
  type: integer
- container: ''
  name: reset
  type: long
- container: ''
  name: async
  type: boolean
- container: ''
  name: success
  type: boolean
- container: ''
  name: credits
  type: schema:MonetaryAmount
- container: ''
  name: amount
  type: integer
- container: ''
  name: refillAmount
  type: integer
- container: ''
  name: refillDay
  type: integer
- container: ''
  name: namespace
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: cost
  type: integer
- container: ''
  name: requestId
  type: string
- container: ''
  name: meta_envelope
  type: reference
- container: ''
  name: data
  type: ''
- container: ''
  name: pagination
  type: ''
- container: ''
  name: cursor
  type: string
- container: ''
  name: hasMore
  type: boolean
property_count: 33
provider_name: Unkey
provider_slug: unkey
slug: unkey-context
source_filename: unkey-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"unkey\": \"https://unkey.com/ontology#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"APIKey\": \"schema:DigitalDocument\",\n    \"APINamespace\": \"schema:SoftwareApplication\",\n    \"Identity\": \"schema:Person\",\n    \"RateLimit\": \"unkey:RateLimit\",\n    \"Permission\": \"unkey:Permission\",\n    \"Role\": \"unkey:Role\",\n    \"Workspace\": \"schema:Organization\",\n\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"enabled\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:long\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:long\"\n    },\n    \"expires\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"\
  xsd:long\"\n    },\n\n    \"apiId\": {\n      \"@id\": \"unkey:apiId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"unkey:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"unkey:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"unkey:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityId\": {\n      \"@id\": \"unkey:identityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@type\": \"@json\"\n    },\n    \"roles\": {\n      \"@id\": \"unkey:roles\",\n      \"@container\": \"@set\"\n    },\n    \"permissions\": {\n      \"@id\": \"unkey:permissions\",\n      \"@container\": \"@set\"\n    },\n    \"hash\": {\n      \"@id\": \"schema:sha256\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"ratelimit\": {\n      \"@id\": \"unkey:ratelimit\",\n      \"@type\": \"unkey:RateLimit\"\
  \n    },\n    \"limit\": {\n      \"@id\": \"unkey:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"duration\": {\n      \"@id\": \"unkey:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remaining\": {\n      \"@id\": \"unkey:remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reset\": {\n      \"@id\": \"unkey:reset\",\n      \"@type\": \"xsd:long\"\n    },\n    \"async\": {\n      \"@id\": \"unkey:async\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"success\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"credits\": {\n      \"@id\": \"unkey:credits\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"refillAmount\": {\n      \"@id\": \"unkey:refillAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"refillDay\": {\n      \"@id\": \"unkey:refillDay\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \n    \"namespace\": {\n      \"@id\": \"unkey:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"unkey:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cost\": {\n      \"@id\": \"unkey:cost\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"requestId\": {\n      \"@id\": \"unkey:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta_envelope\": {\n      \"@id\": \"unkey:responseMeta\",\n      \"@type\": \"@id\"\n    },\n    \"data\": {\n      \"@id\": \"schema:result\"\n    },\n    \"pagination\": {\n      \"@id\": \"schema:ItemList\"\n    },\n    \"cursor\": {\n      \"@id\": \"schema:pageToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasMore\": {\n      \"@id\": \"schema:numberOfPages\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unkey/refs/heads/main/json-ld/unkey-context.jsonld
tags:
- API Keys
- Rate Limiting
- Authentication
- Developer Platform
- Access Control
- Identity
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
