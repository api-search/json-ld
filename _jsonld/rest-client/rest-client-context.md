---
class_count: 8
classes:
- SoftwareApplication
- name
- description
- url
- applicationCategory
- operatingSystem
- codeRepository
- license
context_file: json-ld/rest-client-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rest-client/refs/heads/main/json-ld/rest-client-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rest Client from REST Client.
layout: jsonld
name: Rest Client Context
namespaces:
- prefix: rc
  uri: https://marketplace.visualstudio.com/items/humao.rest-client/vocab#
properties:
- container: ''
  name: HttpRequest
  type: rdfs:Class
- container: ''
  name: Environment
  type: rdfs:Class
- container: ''
  name: RequestVariable
  type: rdfs:Class
- container: ''
  name: GraphQLRequest
  type: rdfs:Class
- container: ''
  name: CurlCommand
  type: rdfs:Class
- container: ''
  name: method
  type: ''
- container: ''
  name: requestUrl
  type: ''
- container: ''
  name: headers
  type: ''
- container: ''
  name: body
  type: ''
- container: ''
  name: environment
  type: rc:Environment
- container: ''
  name: variable
  type: rc:RequestVariable
- container: ''
  name: responseReference
  type: ''
- container: ''
  name: authentication
  type: ''
property_count: 13
provider_name: REST Client
provider_slug: rest-client
slug: rest-client-context
source_filename: rest-client-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rc\": \"https://marketplace.visualstudio.com/items/humao.rest-client/vocab#\",\n    \"SoftwareApplication\": \"SoftwareApplication\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"applicationCategory\": \"applicationCategory\",\n    \"operatingSystem\": \"operatingSystem\",\n    \"codeRepository\": \"codeRepository\",\n    \"license\": \"license\",\n    \"HttpRequest\": {\n      \"@id\": \"rc:HttpRequest\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"Environment\": {\n      \"@id\": \"rc:Environment\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"RequestVariable\": {\n      \"@id\": \"rc:RequestVariable\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"GraphQLRequest\": {\n      \"@id\": \"rc:GraphQLRequest\",\n      \"@type\": \"rdfs:Class\"\n    },\n    \"CurlCommand\": {\n      \"@id\": \"rc:CurlCommand\",\n      \"@type\": \"rdfs:Class\"\n    },\n\
  \    \"method\": {\n      \"@id\": \"rc:method\"\n    },\n    \"requestUrl\": {\n      \"@id\": \"rc:requestUrl\"\n    },\n    \"headers\": {\n      \"@id\": \"rc:headers\"\n    },\n    \"body\": {\n      \"@id\": \"rc:body\"\n    },\n    \"environment\": {\n      \"@id\": \"rc:environment\",\n      \"@type\": \"rc:Environment\"\n    },\n    \"variable\": {\n      \"@id\": \"rc:variable\",\n      \"@type\": \"rc:RequestVariable\"\n    },\n    \"responseReference\": {\n      \"@id\": \"rc:responseReference\"\n    },\n    \"authentication\": {\n      \"@id\": \"rc:authentication\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rest-client/refs/heads/main/json-ld/rest-client-context.jsonld
tags:
- Clients
- HTTP Client
- IDE Extension
- VS Code
- API Testing
- JSON-LD
- Linked Data
- Semantic Web
---
