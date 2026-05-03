---
api_specs:
- filename: swaggerhub-registry-api-openapi.yml
  format: yaml
  label: SwaggerHub Registry API
  slug: swaggerhub-registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-registry-api-openapi.yml
- filename: swaggerhub-user-management-openapi.yml
  format: yaml
  label: SwaggerHub User Management API
  slug: swaggerhub-user-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/openapi/swaggerhub-user-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/swaggerhub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/json-ld/swaggerhub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Swaggerhub from SwaggerHub.
layout: jsonld
name: Swaggerhub Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: swaggerhub
  uri: https://api-evangelist.github.io/swaggerhub/vocab#
properties:
- container: ''
  name: ApiRegistry
  type: reference
- container: ''
  name: ApiDefinition
  type: reference
- container: ''
  name: ApiVersion
  type: reference
- container: ''
  name: Domain
  type: reference
- container: ''
  name: Template
  type: reference
- container: ''
  name: Project
  type: reference
- container: ''
  name: Integration
  type: reference
- container: ''
  name: Organization
  type: reference
- container: ''
  name: Team
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: owner
  type: reference
- container: ''
  name: dateCreated
  type: dateTime
- container: ''
  name: dateModified
  type: dateTime
- container: ''
  name: version
  type: ''
- container: ''
  name: identifier
  type: ''
- container: ''
  name: license
  type: reference
- container: ''
  name: specType
  type: ''
- container: ''
  name: visibility
  type: ''
- container: ''
  name: published
  type: ''
- container: ''
  name: lifecycle
  type: ''
- container: ''
  name: integrationType
  type: ''
- container: ''
  name: organizationRole
  type: ''
- container: ''
  name: standardizationScore
  type: ''
property_count: 25
provider_name: SwaggerHub
provider_slug: swaggerhub
slug: swaggerhub-context
source_filename: swaggerhub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"swaggerhub\": \"https://api-evangelist.github.io/swaggerhub/vocab#\",\n\n    \"ApiRegistry\": { \"@id\": \"swaggerhub:ApiRegistry\", \"@type\": \"@id\" },\n    \"ApiDefinition\": { \"@id\": \"swaggerhub:ApiDefinition\", \"@type\": \"@id\" },\n    \"ApiVersion\": { \"@id\": \"swaggerhub:ApiVersion\", \"@type\": \"@id\" },\n    \"Domain\": { \"@id\": \"swaggerhub:Domain\", \"@type\": \"@id\" },\n    \"Template\": { \"@id\": \"swaggerhub:Template\", \"@type\": \"@id\" },\n    \"Project\": { \"@id\": \"swaggerhub:Project\", \"@type\": \"@id\" },\n    \"Integration\": { \"@id\": \"swaggerhub:Integration\", \"@type\": \"@id\" },\n    \"Organization\": { \"@id\": \"schema:Organization\", \"@type\": \"@id\" },\n    \"Team\": { \"@id\": \"swaggerhub:Team\", \"@type\": \"@id\" },\n\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"\
  url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"owner\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n    \"dateCreated\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"dateModified\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"version\": { \"@id\": \"schema:version\" },\n    \"identifier\": { \"@id\": \"schema:identifier\" },\n    \"license\": { \"@id\": \"schema:license\", \"@type\": \"@id\" },\n\n    \"specType\": { \"@id\": \"swaggerhub:specType\" },\n    \"visibility\": { \"@id\": \"swaggerhub:visibility\" },\n    \"published\": { \"@id\": \"swaggerhub:published\" },\n    \"lifecycle\": { \"@id\": \"swaggerhub:lifecycle\" },\n    \"integrationType\": { \"@id\": \"swaggerhub:integrationType\" },\n    \"organizationRole\": { \"@id\": \"swaggerhub:organizationRole\" },\n    \"standardizationScore\": { \"@id\": \"swaggerhub:standardizationScore\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/swaggerhub/refs/heads/main/json-ld/swaggerhub-context.jsonld
tags:
- API Design
- API Management
- API Registry
- Documentation
- OpenAPI
- SmartBear
- JSON-LD
- Linked Data
- Semantic Web
---
