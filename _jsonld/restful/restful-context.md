---
class_count: 13
classes:
- RESTfulAPI
- Constraint
- MaturityLevel
- ResourcePattern
- id
- type
- name
- description
- version
- authentication
- constraint
- title
- definition
context_file: json-ld/restful-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restful/refs/heads/main/json-ld/restful-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restful from RESTful.
layout: jsonld
name: Restful Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: oa
  uri: http://www.w3.org/ns/oa#
- prefix: rest
  uri: https://api-evangelist.github.io/restful/vocab/
properties:
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: documentationUrl
  type: reference
- container: ''
  name: specificationUrl
  type: reference
- container: ''
  name: maturityLevel
  type: integer
- container: list
  name: tags
  type: ''
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 7
provider_name: RESTful
provider_slug: restful
slug: restful-context
source_filename: restful-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"oa\": \"http://www.w3.org/ns/oa#\",\n    \"rest\": \"https://api-evangelist.github.io/restful/vocab/\",\n\n    \"RESTfulAPI\": \"schema:WebAPI\",\n    \"Constraint\": \"rest:Constraint\",\n    \"MaturityLevel\": \"rest:MaturityLevel\",\n    \"ResourcePattern\": \"rest:ResourcePattern\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"baseUrl\": {\n      \"@id\": \"hydra:entrypoint\",\n      \"@type\": \"@id\"\n    },\n    \"documentationUrl\": {\n      \"@id\": \"hydra:apiDocumentation\",\n      \"@type\": \"@id\"\n    },\n    \"specificationUrl\": {\n      \"@id\": \"schema:schemaUrl\",\n      \"@type\":\
  \ \"@id\"\n    },\n    \"authentication\": \"rest:authentication\",\n    \"maturityLevel\": {\n      \"@id\": \"rest:maturityLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"constraint\": \"rest:constraint\",\n    \"title\": \"dcterms:title\",\n    \"definition\": \"dcterms:description\",\n    \"created\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restful/refs/heads/main/json-ld/restful-context.jsonld
tags:
- Architecture
- HTTP
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
