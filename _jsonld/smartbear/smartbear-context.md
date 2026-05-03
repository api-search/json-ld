---
api_specs:
- filename: smartbear-swaggerhub-openapi.yml
  format: yaml
  label: SwaggerHub API
  slug: swaggerhub
  spec_type: OpenAPI
  url: https://openapi/smartbear-swaggerhub-openapi.yml
class_count: 15
classes:
- name
- description
- ApiDefinition
- versions
- tags
- Organization
- Project
- Integration
- Domain
- members
- role
- integrationType
- SwaggerHub
- ReadyAPI
- PactFlow
context_file: json-ld/smartbear-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/json-ld/smartbear-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smartbear from SmartBear.
layout: jsonld
name: Smartbear Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: smartbear
  uri: https://api-evangelist.github.io/smartbear/vocab#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: owner
  type: reference
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: swaggerUrl
  type: reference
- container: ''
  name: enabled
  type: boolean
property_count: 7
provider_name: SmartBear
provider_slug: smartbear
slug: smartbear-context
source_filename: smartbear-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"smartbear\": \"https://api-evangelist.github.io/smartbear/vocab#\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"ApiDefinition\": \"schema:TechArticle\",\n    \"owner\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"versions\": \"schema:version\",\n    \"isPrivate\": {\n      \"@id\": \"smartbear:isPrivate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": \"schema:keywords\",\n    \"swaggerUrl\": {\n      \"@id\": \"schema:mainEntityOfPage\",\n      \"@type\":\
  \ \"@id\"\n    },\n\n    \"Organization\": \"schema:Organization\",\n    \"Project\": \"schema:Project\",\n    \"Integration\": \"schema:SoftwareApplication\",\n    \"Domain\": \"schema:DefinedTerm\",\n\n    \"members\": \"schema:member\",\n    \"role\": \"schema:roleName\",\n    \"enabled\": {\n      \"@id\": \"smartbear:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"integrationType\": \"schema:additionalType\",\n\n    \"SwaggerHub\": \"schema:SoftwareApplication\",\n    \"ReadyAPI\": \"schema:SoftwareApplication\",\n    \"PactFlow\": \"schema:SoftwareApplication\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smartbear/refs/heads/main/json-ld/smartbear-context.jsonld
tags:
- API Design
- API Documentation
- API Testing
- Contract Testing
- Governance
- Monitoring
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
