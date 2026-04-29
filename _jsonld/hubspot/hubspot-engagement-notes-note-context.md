---
class_count: 6
classes:
- Note
- NoteCollectionResponse
- NoteSearchResponse
- NoteCreateRequest
- NoteUpdateRequest
- NoteSearchRequest
context_file: json-ld/hubspot-engagement-notes-note-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-note-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Note from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Note Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: propertiesWithHistory
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: ''
  name: archivedAt
  type: dateTime
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: total
  type: integer
- container: set
  name: associations
  type: reference
- container: set
  name: filterGroups
  type: reference
- container: set
  name: sorts
  type: reference
- container: ''
  name: query
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: after
  type: string
property_count: 16
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-note-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Note\": \"hubspot:Note\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"propertiesWithHistory\": {\n      \"@id\": \"hubspot:propertiesWithHistory\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"archivedAt\": {\n      \"@id\": \"hubspot:archivedAt\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"NoteCollectionResponse\": \"hubspot:NoteCollectionResponse\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"NoteSearchResponse\": \"hubspot:NoteSearchResponse\",\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"NoteCreateRequest\": \"hubspot:NoteCreateRequest\",\n    \"associations\": {\n      \"@id\": \"hubspot:associations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"NoteUpdateRequest\": \"hubspot:NoteUpdateRequest\",\n    \"NoteSearchRequest\": \"hubspot:NoteSearchRequest\",\n    \"filterGroups\": {\n      \"@id\": \"hubspot:filterGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sorts\": {\n      \"@id\": \"hubspot:sorts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\
  \n    },\n    \"query\": {\n      \"@id\": \"hubspot:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"hubspot:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-note-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
