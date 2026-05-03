---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Speakeasy
  slug: speakeasy
  spec_type: OpenAPI
  url: https://www.speakeasy.com/openapi.yaml
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/speakeasy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/speakeasy/refs/heads/main/json-ld/speakeasy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Speakeasy from Speakeasy.
layout: jsonld
name: Speakeasy Context
namespaces:
- prefix: speakeasy
  uri: https://www.speakeasy.com/vocab/
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
  name: Workspace
  type: reference
- container: ''
  name: Organization
  type: reference
- container: ''
  name: Token
  type: reference
- container: ''
  name: PublishingToken
  type: reference
- container: ''
  name: CodeSample
  type: reference
- container: ''
  name: Artifact
  type: reference
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: organizationId
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: accountType
  type: '@vocab'
- container: ''
  name: telemetryDisabled
  type: boolean
- container: ''
  name: targetId
  type: string
- container: ''
  name: validUntil
  type: dateTime
- container: ''
  name: namespace
  type: string
- container: list
  name: featureFlags
  type: ''
property_count: 17
provider_name: Speakeasy
provider_slug: speakeasy
slug: speakeasy-context
source_filename: speakeasy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"speakeasy\": \"https://www.speakeasy.com/vocab/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"createdAt\": {\n      \"@id\": \"speakeasy:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"speakeasy:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Workspace\": {\n      \"@id\": \"speakeasy:Workspace\",\n      \"@type\": \"@id\"\n    },\n    \"Organization\": {\n      \"@id\": \"speakeasy:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"Token\": {\n      \"@id\": \"speakeasy:Token\",\n      \"@type\": \"@id\"\n    },\n    \"PublishingToken\": {\n      \"@id\": \"speakeasy:PublishingToken\",\n      \"@type\": \"@id\"\n    },\n    \"CodeSample\": {\n      \"@id\": \"speakeasy:CodeSample\",\n      \"@type\": \"@id\"\n    },\n    \"Artifact\": {\n      \"@id\": \"speakeasy:Artifact\",\n      \"\
  @type\": \"@id\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"speakeasy:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationId\": {\n      \"@id\": \"speakeasy:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"speakeasy:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"speakeasy:accountType\",\n      \"@type\": \"@vocab\"\n    },\n    \"telemetryDisabled\": {\n      \"@id\": \"speakeasy:telemetryDisabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"targetId\": {\n      \"@id\": \"speakeasy:targetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validUntil\": {\n      \"@id\": \"speakeasy:validUntil\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"namespace\": {\n      \"@id\": \"speakeasy:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"featureFlags\": {\n      \"@id\": \"speakeasy:featureFlags\",\n      \"@container\": \"@list\"\n    },\n    \"xsd\"\
  : \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/speakeasy/refs/heads/main/json-ld/speakeasy-context.jsonld
tags:
- AI
- Documentation
- MCP
- Platform
- SDKs
- Terraform
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
