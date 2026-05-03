---
api_specs:
- filename: sentry-api-openapi.yml
  format: yaml
  label: Sentry Error Monitoring API
  slug: sentry-error-monitoring-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/openapi/sentry-api-openapi.yml
- filename: sentry-webhooks-asyncapi.yml
  format: yaml
  label: Sentry Integration Platform API
  slug: sentry-integration-platform-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/asyncapi/sentry-webhooks-asyncapi.yml
class_count: 25
classes:
- Issue
- Event
- Project
- Organization
- Release
- User
- id
- shortId
- title
- culprit
- level
- status
- platform
- type
- metadata
- count
- userCount
- numComments
- assignedTo
- tags
- version
- ref
- name
- slug
- message
context_file: json-ld/sentry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/json-ld/sentry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sentry from Sentry.
layout: jsonld
name: Sentry Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sentry
  uri: https://sentry.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: permalink
  type: reference
- container: ''
  name: firstSeen
  type: dateTime
- container: ''
  name: lastSeen
  type: dateTime
- container: ''
  name: dateReleased
  type: dateTime
- container: ''
  name: organization
  type: reference
- container: ''
  name: project
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
property_count: 8
provider_name: Sentry
provider_slug: sentry
slug: sentry-context
source_filename: sentry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sentry\": \"https://sentry.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Issue\": \"sentry:Issue\",\n    \"Event\": \"sentry:Event\",\n    \"Project\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\",\n    \"Release\": \"schema:SoftwareApplication\",\n    \"User\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"shortId\": \"sentry:shortId\",\n    \"title\": \"schema:name\",\n    \"culprit\": \"sentry:culprit\",\n    \"permalink\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"level\": \"sentry:severityLevel\",\n    \"status\": \"sentry:status\",\n    \"platform\": \"schema:programmingLanguage\",\n    \"type\": \"sentry:issueType\",\n    \"metadata\": \"sentry:metadata\",\n\n    \"count\": \"sentry:eventCount\",\n    \"userCount\": \"sentry:affectedUserCount\",\n    \"numComments\": \"sentry:commentCount\"\
  ,\n    \"firstSeen\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"assignedTo\": \"schema:contributor\",\n    \"tags\": \"schema:keywords\",\n\n    \"version\": \"schema:version\",\n    \"dateReleased\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ref\": \"sentry:gitRef\",\n\n    \"name\": \"schema:name\",\n    \"slug\": \"sentry:slug\",\n    \"organization\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"@id\"\n    },\n    \"project\": {\n      \"@id\": \"sentry:project\",\n      \"@type\": \"@id\"\n    },\n\n    \"message\": \"schema:description\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/json-ld/sentry-context.jsonld
tags:
- Error Monitoring
- Debugging
- Observability
- Application Performance Management
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
