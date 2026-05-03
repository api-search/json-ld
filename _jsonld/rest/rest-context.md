---
class_count: 9
classes:
- Resource
- Representation
- Endpoint
- API
- Operation
- mediaType
- description
- name
- version
context_file: json-ld/rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/json-ld/rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rest from REST.
layout: jsonld
name: Rest Context
namespaces:
- prefix: rest
  uri: https://restfulapi.net/ns/
- prefix: http
  uri: http://www.w3.org/2011/http#
- prefix: iana
  uri: https://www.iana.org/assignments/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
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
- container: ''
  name: url
  type: reference
- container: ''
  name: documentation
  type: reference
property_count: 5
provider_name: REST
provider_slug: rest
slug: rest-context
source_filename: rest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rest\": \"https://restfulapi.net/ns/\",\n    \"http\": \"http://www.w3.org/2011/http#\",\n    \"iana\": \"https://www.iana.org/assignments/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Resource\": \"rest:Resource\",\n    \"Representation\": \"rest:Representation\",\n    \"Endpoint\": \"schema:EntryPoint\",\n    \"API\": \"schema:WebAPI\",\n    \"Operation\": \"schema:Action\",\n\n    \"method\": {\n      \"@id\": \"http:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"rest:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"http:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mediaType\": \"schema:encodingFormat\",\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\",\n    \"version\": \"schema:version\",\n    \"url\": {\n  \
  \    \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"documentation\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/json-ld/rest-context.jsonld
tags:
- API Design
- Architecture
- HTTP
- REST
- RESTful
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
