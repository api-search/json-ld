---
class_count: 7
classes:
- CRMAccount
- CRMContact
- Lead
- Opportunity
- Engagement
- Note
- Stage
context_file: json-ld/merge-crm-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-crm-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Merge Crm Api from Merge.
layout: jsonld
name: Merge Crm Api Context
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
- container: ''
  name: industry
  type: string
- container: ''
  name: website
  type: reference
- container: ''
  name: numberOfEmployees
  type: integer
- container: ''
  name: owner
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: account
  type: reference
- container: ''
  name: leadSource
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: stage
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: closeDate
  type: dateTime
- container: ''
  name: content
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: lastActivityAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: remoteWasDeleted
  type: boolean
property_count: 22
provider_name: Merge
provider_slug: merge
slug: merge-crm-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"merge\": \"https://api.merge.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"CRMAccount\": \"merge:CRMAccount\",\n    \"CRMContact\": \"merge:CRMContact\",\n    \"Lead\": \"merge:Lead\",\n    \"Opportunity\": \"merge:Opportunity\",\n    \"Engagement\": \"merge:Engagement\",\n    \"Note\": \"merge:Note\",\n    \"Stage\": \"merge:Stage\",\n\n    \"id\": { \"@id\": \"dcterms:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"industry\": { \"@id\": \"merge:industry\", \"@type\": \"xsd:string\" },\n    \"website\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"numberOfEmployees\": { \"@id\": \"schema:numberOfEmployees\", \"@type\": \"xsd:integer\"\
  \ },\n    \"owner\": { \"@id\": \"merge:owner\", \"@type\": \"@id\" },\n    \"firstName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"lastName\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"account\": { \"@id\": \"merge:account\", \"@type\": \"@id\" },\n    \"leadSource\": { \"@id\": \"merge:lead_source\", \"@type\": \"xsd:string\" },\n    \"amount\": { \"@id\": \"merge:amount\", \"@type\": \"xsd:integer\" },\n    \"stage\": { \"@id\": \"merge:stage\", \"@type\": \"@id\" },\n    \"status\": { \"@id\": \"merge:status\", \"@type\": \"xsd:string\" },\n    \"closeDate\": { \"@id\": \"merge:close_date\", \"@type\": \"xsd:dateTime\" },\n    \"content\": { \"@id\": \"merge:content\", \"@type\": \"xsd:string\" },\n    \"subject\": { \"@id\": \"merge:subject\", \"@type\": \"xsd:string\" },\n    \"direction\": { \"@id\": \"merge:direction\", \"@type\": \"xsd:string\" },\n    \"lastActivityAt\": { \"@id\": \"merge:last_activity_at\", \"@type\":\
  \ \"xsd:dateTime\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"modifiedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"remoteWasDeleted\": { \"@id\": \"merge:remote_was_deleted\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/merge/refs/heads/main/json-ld/merge-crm-api-context.jsonld
tags:
- Integrations
- Platform
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
