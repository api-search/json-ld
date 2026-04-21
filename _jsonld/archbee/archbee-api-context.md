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
