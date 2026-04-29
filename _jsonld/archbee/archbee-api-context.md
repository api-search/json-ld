---
class_count: 9
classes:
- ErrorResponse
- Space
- SpaceRequest
- SpaceList
- Page
- PageRequest
- PageList
- Member
- MemberList
context_file: json-ld/archbee-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/json-ld/archbee-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Archbee Api from Archbee.
layout: jsonld
name: Archbee Api Context
namespaces:
- prefix: archbee
  uri: https://api.archbee.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: spaces
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: spaceId
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: pages
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: members
  type: string
property_count: 21
provider_name: Archbee
provider_slug: archbee
slug: archbee-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"archbee\": \"https://api.archbee.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"archbee:ErrorResponse\",\n    \"message\": {\n      \"@id\": \"archbee:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"archbee:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Space\": \"archbee:Space\",\n    \"id\": {\n      \"@id\": \"archbee:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"archbee:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"archbee:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"archbee:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"archbee:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageCount\": {\n      \"@id\"\
  : \"archbee:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"archbee:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SpaceRequest\": \"archbee:SpaceRequest\",\n    \"SpaceList\": \"archbee:SpaceList\",\n    \"spaces\": {\n      \"@id\": \"archbee:spaces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"archbee:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Page\": \"archbee:Page\",\n    \"title\": {\n      \"@id\": \"archbee:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"archbee:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"archbee:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spaceId\": {\n      \"@id\": \"archbee:spaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"archbee:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\"\
  : {\n      \"@id\": \"archbee:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PageRequest\": \"archbee:PageRequest\",\n    \"PageList\": \"archbee:PageList\",\n    \"pages\": {\n      \"@id\": \"archbee:pages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Member\": \"archbee:Member\",\n    \"email\": {\n      \"@id\": \"archbee:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"archbee:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MemberList\": \"archbee:MemberList\",\n    \"members\": {\n      \"@id\": \"archbee:members\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/json-ld/archbee-api-context.jsonld
tags:
- API Documentation
- Documentation Platform
- Knowledge Base
- Technical Writing
- Developer Docs
- JSON-LD
- Linked Data
- Semantic Web
---
