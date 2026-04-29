---
class_count: 4
classes:
- Ticket
- Comment
- Project
- Attachment
context_file: json-ld/merge-ticketing-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-ticketing-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge Ticketing Api from Merge.
layout: jsonld
name: Merge Ticketing Api Context
namespaces:
- prefix: merge
  uri: https://api.merge.dev/schema/
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
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: set
  name: assignees
  type: reference
- container: ''
  name: creator
  type: reference
- container: ''
  name: dueDate
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: ticketType
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: ticketUrl
  type: reference
- container: ''
  name: body
  type: string
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: fileName
  type: string
- container: ''
  name: fileUrl
  type: reference
- container: ''
  name: contentType
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: remoteWasDeleted
  type: boolean
property_count: 20
provider_name: Merge
provider_slug: merge
slug: merge-ticketing-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Ticket\": \"merge:Ticket\",\n    \"Comment\": \"merge:Comment\",\n    \"Project\": \"merge:Project\",\n    \"Attachment\": \"merge:Attachment\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"assignees\": { \"@id\": \"merge:assignees\", \"@container\": \"@set\", \"@type\": \"@id\" },\n    \"creator\": { \"@id\": \"merge:creator\", \"@type\": \"@id\" },\n    \"dueDate\": { \"@id\": \"merge:due_date\", \"@type\": \"xsd:dateTime\" },\n    \"status\": { \"@id\": \"merge:status\", \"@type\": \"xsd:string\" },\n    \"priority\": { \"@id\": \"\
  merge:priority\", \"@type\": \"xsd:string\" },\n    \"ticketType\": { \"@id\": \"merge:ticket_type\", \"@type\": \"xsd:string\" },\n    \"tags\": { \"@id\": \"merge:tags\", \"@container\": \"@set\", \"@type\": \"xsd:string\" },\n    \"completedAt\": { \"@id\": \"merge:completed_at\", \"@type\": \"xsd:dateTime\" },\n    \"ticketUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"body\": { \"@id\": \"merge:body\", \"@type\": \"xsd:string\" },\n    \"isPrivate\": { \"@id\": \"merge:is_private\", \"@type\": \"xsd:boolean\" },\n    \"fileName\": { \"@id\": \"merge:file_name\", \"@type\": \"xsd:string\" },\n    \"fileUrl\": { \"@id\": \"merge:file_url\", \"@type\": \"@id\" },\n    \"contentType\": { \"@id\": \"merge:content_type\", \"@type\": \"xsd:string\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\"\
  , \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-ticketing-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
