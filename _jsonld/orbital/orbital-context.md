---
api_specs:
- filename: orbital-query-api-openapi.yml
  format: yaml
  label: Orbital Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/openapi/orbital-query-api-openapi.yml
- filename: orbital-schema-management-api-openapi.yml
  format: yaml
  label: Orbital Schema Management API
  slug: schema-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/openapi/orbital-schema-management-api-openapi.yml
class_count: 35
classes:
- Query
- Schema
- Service
- Connection
- Type
- Cache
- queryId
- query
- resultMode
- duration
- qualifiedName
- kind
- schemaId
- connectionId
- connectionType
- connectionUrl
- protocol
- operationCount
- status
- source
- content
- fields
- sources
- operations
- returnType
- nullable
- authentication
- credentials
- types
- name
- description
- url
- version
- createdAt
- updatedAt
context_file: json-ld/orbital-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/json-ld/orbital-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Orbital from Orbital.
layout: jsonld
name: Orbital Context
namespaces:
- prefix: orbital
  uri: https://orbitalhq.com/ns/
- prefix: taxi
  uri: https://taxilang.org/ns/
properties: []
property_count: 0
provider_name: Orbital
provider_slug: orbital
slug: orbital-context
source_filename: orbital-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"orbital\": \"https://orbitalhq.com/ns/\",\n    \"taxi\": \"https://taxilang.org/ns/\",\n    \"Query\": \"orbital:Query\",\n    \"Schema\": \"orbital:Schema\",\n    \"Service\": \"orbital:Service\",\n    \"Connection\": \"orbital:Connection\",\n    \"Type\": \"orbital:Type\",\n    \"Cache\": \"orbital:Cache\",\n    \"queryId\": \"orbital:queryId\",\n    \"query\": \"orbital:query\",\n    \"resultMode\": \"orbital:resultMode\",\n    \"duration\": \"orbital:duration\",\n    \"qualifiedName\": \"orbital:qualifiedName\",\n    \"kind\": \"orbital:kind\",\n    \"schemaId\": \"orbital:schemaId\",\n    \"connectionId\": \"orbital:connectionId\",\n    \"connectionType\": \"orbital:connectionType\",\n    \"connectionUrl\": \"orbital:connectionUrl\",\n    \"protocol\": \"orbital:protocol\",\n    \"operationCount\": \"orbital:operationCount\",\n    \"status\": \"orbital:status\",\n    \"source\": \"orbital:source\",\n\
  \    \"content\": \"orbital:content\",\n    \"fields\": \"orbital:fields\",\n    \"sources\": \"orbital:sources\",\n    \"operations\": \"orbital:operations\",\n    \"returnType\": \"orbital:returnType\",\n    \"nullable\": \"orbital:nullable\",\n    \"authentication\": \"orbital:authentication\",\n    \"credentials\": \"orbital:credentials\",\n    \"types\": \"orbital:types\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/json-ld/orbital-context.jsonld
tags:
- Data
- Gateways
- JSON-LD
- Linked Data
- Semantic Web
---
