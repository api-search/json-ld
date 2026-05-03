---
class_count: 6
classes:
- SoftwareApplication
- name
- description
- url
- version
- programmingLanguage
context_file: json-ld/stoplight-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stoplight/refs/heads/main/json-ld/stoplight-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stoplight from Stoplight.
layout: jsonld
name: Stoplight Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: Workspace
  uri: https://stoplight.io/schema/Workspace
- prefix: Project
  uri: https://stoplight.io/schema/Project
- prefix: APISpec
  uri: https://stoplight.io/schema/APISpec
- prefix: StyleGuide
  uri: https://stoplight.io/schema/StyleGuide
- prefix: MockServer
  uri: https://stoplight.io/schema/MockServer
- prefix: SpectralRule
  uri: https://stoplight.io/schema/SpectralRule
- prefix: projects
  uri: https://stoplight.io/schema/projects
- prefix: openApiVersion
  uri: https://stoplight.io/schema/openApiVersion
- prefix: asyncApiVersion
  uri: https://stoplight.io/schema/asyncApiVersion
- prefix: rulesets
  uri: https://stoplight.io/schema/rulesets
- prefix: severity
  uri: https://stoplight.io/schema/severity
- prefix: given
  uri: https://stoplight.io/schema/given
- prefix: then
  uri: https://stoplight.io/schema/then
properties:
- container: ''
  name: APIDesignTool
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: repository
  type: reference
- container: ''
  name: workspace
  type: reference
- container: ''
  name: mockServer
  type: reference
- container: ''
  name: documentation
  type: reference
- container: ''
  name: npmPackage
  type: reference
property_count: 7
provider_name: Stoplight
provider_slug: stoplight
slug: stoplight-context
source_filename: stoplight-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://stoplight.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"APIDesignTool\": {\n      \"@id\": \"https://stoplight.io/schema/APIDesignTool\",\n      \"@type\": \"@id\"\n    },\n    \"Workspace\": \"https://stoplight.io/schema/Workspace\",\n    \"Project\": \"https://stoplight.io/schema/Project\",\n    \"APISpec\": \"https://stoplight.io/schema/APISpec\",\n    \"StyleGuide\": \"https://stoplight.io/schema/StyleGuide\",\n    \"MockServer\": \"https://stoplight.io/schema/MockServer\",\n    \"SpectralRule\": \"https://stoplight.io/schema/SpectralRule\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n   \
  \ \"license\": {\n      \"@id\": \"doap:license\",\n      \"@type\": \"@id\"\n    },\n    \"repository\": {\n      \"@id\": \"doap:repository\",\n      \"@type\": \"@id\"\n    },\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"workspace\": {\n      \"@id\": \"https://stoplight.io/schema/workspace\",\n      \"@type\": \"@id\"\n    },\n    \"projects\": \"https://stoplight.io/schema/projects\",\n    \"openApiVersion\": \"https://stoplight.io/schema/openApiVersion\",\n    \"asyncApiVersion\": \"https://stoplight.io/schema/asyncApiVersion\",\n    \"rulesets\": \"https://stoplight.io/schema/rulesets\",\n    \"severity\": \"https://stoplight.io/schema/severity\",\n    \"given\": \"https://stoplight.io/schema/given\",\n    \"then\": \"https://stoplight.io/schema/then\",\n    \"mockServer\": {\n      \"@id\": \"https://stoplight.io/schema/mockServer\",\n      \"@type\": \"@id\"\n    },\n    \"documentation\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"\
  @id\"\n    },\n    \"npmPackage\": {\n      \"@id\": \"https://stoplight.io/schema/npmPackage\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stoplight/refs/heads/main/json-ld/stoplight-context.jsonld
tags:
- API Design
- API Documentation
- API Governance
- AsyncAPI
- Design-First
- Linting
- Mock Servers
- OpenAPI
- Style Guides
- JSON-LD
- Linked Data
- Semantic Web
---
