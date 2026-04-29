---
class_count: 4
classes:
- Repository
- MockServer
- name
- description
context_file: json-ld/apigit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/json-ld/apigit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apigit from APIGit.
layout: jsonld
name: Apigit Context
namespaces:
- prefix: apigit
  uri: https://apigit.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: status
  type: string
property_count: 3
provider_name: APIGit
provider_slug: apigit
slug: apigit-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apigit\": \"https://apigit.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Repository\": \"apigit:Repository\",\n    \"MockServer\": \"apigit:MockServer\",\n    \"id\": {\n      \"@id\": \"apigit:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"visibility\": {\n      \"@id\": \"apigit:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"apigit:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apigit/refs/heads/main/json-ld/apigit-context.jsonld
tags:
- API Design
- API Lifecycle
- Documentation
- Git
- Governance
- Mocking
- Platform
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
