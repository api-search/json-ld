---
api_specs:
- filename: trelica-rest-api-openapi.yml
  format: yaml
  label: Trelica REST API
  slug: trelica
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/openapi/trelica-rest-api-openapi.yml
class_count: 23
classes:
- Application
- Person
- Contract
- Workflow
- Asset
- AuditEntry
- id
- name
- description
- email
- displayName
- department
- jobTitle
- active
- currency
- category
- status
- vendor
- actorName
- action
- resourceType
- changes
- trigger
context_file: json-ld/trelica-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/json-ld/trelica-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trelica from Trelica.
layout: jsonld
name: Trelica Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: trelica
  uri: https://trelica.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: vendorUrl
  type: reference
- container: ''
  name: userCount
  type: integer
- container: ''
  name: annualCost
  type: decimal
- container: ''
  name: annualValue
  type: decimal
- container: ''
  name: applicationId
  type: reference
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: manager
  type: reference
- container: ''
  name: lastModifiedDtm
  type: dateTime
- container: ''
  name: lastLoginDtm
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: actorId
  type: reference
- container: ''
  name: resourceId
  type: reference
- container: set
  name: results
  type: ''
- container: ''
  name: next
  type: reference
property_count: 15
provider_name: Trelica
provider_slug: trelica
slug: trelica-context
source_filename: trelica-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"trelica\": \"https://trelica.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Application\": \"schema:SoftwareApplication\",\n    \"Person\": \"schema:Person\",\n    \"Contract\": \"trelica:Contract\",\n    \"Workflow\": \"trelica:Workflow\",\n    \"Asset\": \"trelica:Asset\",\n    \"AuditEntry\": \"trelica:AuditEntry\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"displayName\": \"schema:name\",\n    \"department\": \"schema:department\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"active\": \"schema:isRelatedTo\",\n    \"vendorUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"userCount\": { \"@id\": \"trelica:userCount\", \"@type\": \"xsd:integer\" },\n    \"annualCost\": { \"@id\": \"trelica:annualCost\", \"@type\": \"xsd:decimal\" },\n   \
  \ \"annualValue\": { \"@id\": \"trelica:annualValue\", \"@type\": \"xsd:decimal\" },\n    \"currency\": \"trelica:currency\",\n    \"category\": \"schema:category\",\n    \"status\": \"trelica:status\",\n    \"vendor\": \"schema:provider\",\n    \"applicationId\": { \"@id\": \"trelica:applicationId\", \"@type\": \"@id\" },\n    \"startDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"endDate\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:date\" },\n    \"manager\": { \"@id\": \"schema:worksFor\", \"@type\": \"@id\" },\n    \"lastModifiedDtm\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"lastLoginDtm\": { \"@id\": \"trelica:lastLoginDtm\", \"@type\": \"xsd:dateTime\" },\n    \"timestamp\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"actorId\": { \"@id\": \"trelica:actorId\", \"@type\": \"@id\" },\n    \"actorName\": \"trelica:actorName\",\n    \"action\": \"trelica:action\",\n    \"resourceType\": \"\
  trelica:resourceType\",\n    \"resourceId\": { \"@id\": \"trelica:resourceId\", \"@type\": \"@id\" },\n    \"changes\": \"trelica:changes\",\n    \"trigger\": \"trelica:trigger\",\n\n    \"results\": { \"@id\": \"trelica:results\", \"@container\": \"@set\" },\n    \"next\": { \"@id\": \"trelica:next\", \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/json-ld/trelica-context.jsonld
tags:
- Contract Management
- IT Management
- License Management
- SaaS Management
- Software Asset Management
- JSON-LD
- Linked Data
- Semantic Web
---
