---
api_specs:
- filename: microsoft-teams-graph-api.yaml
  format: yaml
  label: Microsoft Graph Teams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/openapi/microsoft-teams-graph-api.yaml
class_count: 9
classes:
- Team
- Channel
- ChatMessage
- ConversationMember
- OnlineMeeting
- Call
- name
- description
- email
context_file: json-ld/microsoft-teams-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/json-ld/microsoft-teams-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Teams Graph Api from Microsoft Teams.
layout: jsonld
name: Microsoft Teams Graph Api Context
namespaces:
- prefix: ms
  uri: https://graph.microsoft.com/schema/
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
  name: displayName
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: isArchived
  type: boolean
- container: ''
  name: createdDateTime
  type: dateTime
- container: ''
  name: lastModifiedDateTime
  type: dateTime
- container: ''
  name: webUrl
  type: reference
- container: ''
  name: membershipType
  type: string
- container: ''
  name: messageType
  type: string
- container: ''
  name: importance
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: body
  type: reference
- container: ''
  name: from
  type: reference
- container: set
  name: roles
  type: ''
- container: ''
  name: userId
  type: string
- container: ''
  name: startDateTime
  type: dateTime
- container: ''
  name: endDateTime
  type: dateTime
- container: ''
  name: joinWebUrl
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: callbackUri
  type: reference
- container: set
  name: requestedModalities
  type: ''
property_count: 22
provider_name: Microsoft Teams
provider_slug: microsoft-teams
slug: microsoft-teams-graph-api-context
source_filename: microsoft-teams-graph-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ms\": \"https://graph.microsoft.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Team\": \"ms:Team\",\n    \"Channel\": \"ms:Channel\",\n    \"ChatMessage\": \"ms:ChatMessage\",\n    \"ConversationMember\": \"ms:ConversationMember\",\n    \"OnlineMeeting\": \"ms:OnlineMeeting\",\n    \"Call\": \"ms:Call\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"id\": { \"@id\": \"ms:id\", \"@type\": \"xsd:string\" },\n    \"displayName\": { \"@id\": \"ms:displayName\", \"@type\": \"xsd:string\" },\n    \"visibility\": { \"@id\": \"ms:visibility\", \"@type\": \"xsd:string\" },\n    \"isArchived\": { \"@id\": \"ms:isArchived\", \"@type\": \"xsd:boolean\" },\n    \"createdDateTime\": { \"@id\": \"ms:createdDateTime\", \"@type\": \"xsd:dateTime\" },\n\
  \    \"lastModifiedDateTime\": { \"@id\": \"ms:lastModifiedDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"webUrl\": { \"@id\": \"ms:webUrl\", \"@type\": \"@id\" },\n    \"membershipType\": { \"@id\": \"ms:membershipType\", \"@type\": \"xsd:string\" },\n    \"messageType\": { \"@id\": \"ms:messageType\", \"@type\": \"xsd:string\" },\n    \"importance\": { \"@id\": \"ms:importance\", \"@type\": \"xsd:string\" },\n    \"subject\": { \"@id\": \"ms:subject\", \"@type\": \"xsd:string\" },\n    \"body\": { \"@id\": \"ms:body\", \"@type\": \"@id\" },\n    \"from\": { \"@id\": \"ms:from\", \"@type\": \"@id\" },\n    \"roles\": { \"@id\": \"ms:roles\", \"@container\": \"@set\" },\n    \"userId\": { \"@id\": \"ms:userId\", \"@type\": \"xsd:string\" },\n    \"startDateTime\": { \"@id\": \"ms:startDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"endDateTime\": { \"@id\": \"ms:endDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"joinWebUrl\": { \"@id\": \"ms:joinWebUrl\", \"@type\": \"@id\" },\n\
  \    \"state\": { \"@id\": \"ms:state\", \"@type\": \"xsd:string\" },\n    \"direction\": { \"@id\": \"ms:direction\", \"@type\": \"xsd:string\" },\n    \"callbackUri\": { \"@id\": \"ms:callbackUri\", \"@type\": \"@id\" },\n    \"requestedModalities\": { \"@id\": \"ms:requestedModalities\", \"@container\": \"@set\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/json-ld/microsoft-teams-graph-api-context.jsonld
tags:
- Chat
- Collaboration
- Communication
- Microsoft 365
- Productivity
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---
