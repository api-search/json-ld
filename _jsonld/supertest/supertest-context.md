---
class_count: 17
classes:
- SoftwareApplication
- SoftwareSourceCode
- name
- description
- url
- version
- license
- programmingLanguage
- codeRepository
- TestAction
- request
- response
- assertion
- Project
- release
- maintainer
- repository
context_file: json-ld/supertest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/supertest/refs/heads/main/json-ld/supertest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Supertest from SuperTest.
layout: jsonld
name: Supertest Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: method
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: statusCode
  type: integer
property_count: 3
provider_name: SuperTest
provider_slug: supertest
slug: supertest-context
source_filename: supertest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://github.com/ladjs/supertest#\",\n    \"schema\": \"https://schema.org/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n    \"license\": \"schema:license\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"TestAction\": \"schema:Action\",\n    \"method\": {\n      \"@id\": \"schema:httpMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"schema:result\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  request\": \"schema:potentialAction\",\n    \"response\": \"schema:result\",\n    \"assertion\": \"schema:expectsAcceptanceOf\",\n    \"Project\": \"doap:Project\",\n    \"release\": \"doap:release\",\n    \"maintainer\": \"doap:maintainer\",\n    \"repository\": \"doap:repository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/supertest/refs/heads/main/json-ld/supertest-context.jsonld
tags:
- Testing
- Functional Testing
- HTTP Testing
- Node.js
- JavaScript
- Open Source
- API Testing
- Integration Testing
- SuperAgent
- Fluent API
- JSON-LD
- Linked Data
- Semantic Web
---
