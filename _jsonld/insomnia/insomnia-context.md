---
api_specs:
- filename: insomnia-mock-server-openapi.yml
  format: yaml
  label: Insomnia Mock Server API
  slug: mock-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/openapi/insomnia-mock-server-openapi.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/insomnia-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/json-ld/insomnia-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Insomnia from Insomnia.
layout: jsonld
name: Insomnia Context
namespaces:
- prefix: insomnia
  uri: https://insomnia.rest/ns/
properties:
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Request
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: MockServer
  type: ''
- container: ''
  name: MockRoute
  type: ''
property_count: 5
provider_name: Insomnia
provider_slug: insomnia
slug: insomnia-context
source_filename: insomnia-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"insomnia\": \"https://insomnia.rest/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Workspace\": {\n      \"@id\": \"insomnia:Workspace\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"scope\": \"insomnia:scope\",\n        \"parentId\": \"insomnia:parentId\",\n        \"isPrivate\": \"insomnia:isPrivate\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\n      }\n    },\n    \"Request\": {\n      \"@id\": \"insomnia:Request\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"method\": \"insomnia:httpMethod\",\n        \"headers\": \"insomnia:headers\",\n        \"parameters\": \"insomnia:parameters\",\n        \"body\": \"insomnia:requestBody\",\n        \"authentication\"\
  : \"insomnia:authentication\",\n        \"parentId\": \"insomnia:parentId\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\n      }\n    },\n    \"Environment\": {\n      \"@id\": \"insomnia:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"data\": \"insomnia:environmentData\",\n        \"color\": \"insomnia:color\",\n        \"parentId\": \"insomnia:parentId\",\n        \"isPrivate\": \"insomnia:isPrivate\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\n      }\n    },\n    \"MockServer\": {\n      \"@id\": \"insomnia:MockServer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"status\": \"insomnia:status\",\n        \"workspaceId\": \"insomnia:workspaceId\",\n        \"specificationSource\": \"insomnia:specificationSource\",\n        \"created\": \"schema:dateCreated\",\n        \"modified\": \"schema:dateModified\"\
  \n      }\n    },\n    \"MockRoute\": {\n      \"@id\": \"insomnia:MockRoute\",\n      \"@context\": {\n        \"method\": \"insomnia:httpMethod\",\n        \"path\": \"insomnia:routePath\",\n        \"statusCode\": \"insomnia:statusCode\",\n        \"responseBody\": \"insomnia:responseBody\",\n        \"contentType\": \"insomnia:contentType\",\n        \"delay\": \"insomnia:delay\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/insomnia/refs/heads/main/json-ld/insomnia-context.jsonld
tags:
- API Design
- CLI
- Clients
- Mocking
- Platform
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
