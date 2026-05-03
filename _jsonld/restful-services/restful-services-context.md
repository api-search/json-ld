---
class_count: 13
classes:
- Resource
- Collection
- Operation
- Link
- Error
- id
- type
- title
- description
- detail
- method
- name
- version
context_file: json-ld/restful-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restful-services/refs/heads/main/json-ld/restful-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restful Services from RESTful Services.
layout: jsonld
name: Restful Services Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rest
  uri: https://api-evangelist.github.io/restful-services/vocab/
properties:
- container: ''
  name: href
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: status
  type: integer
- container: ''
  name: expects
  type: reference
- container: ''
  name: returns
  type: reference
- container: list
  name: member
  type: ''
- container: ''
  name: totalItems
  type: integer
- container: ''
  name: url
  type: reference
property_count: 9
provider_name: RESTful Services
provider_slug: restful-services
slug: restful-services-context
source_filename: restful-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rest\": \"https://api-evangelist.github.io/restful-services/vocab/\",\n\n    \"Resource\": \"hydra:Resource\",\n    \"Collection\": \"hydra:Collection\",\n    \"Operation\": \"hydra:Operation\",\n    \"Link\": \"hydra:Link\",\n    \"Error\": \"schema:Error\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"href\": {\n      \"@id\": \"hydra:apiDocumentation\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"title\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"status\": {\n      \"@id\": \"schema:status\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"detail\": \"schema:description\",\n    \"method\": \"hydra:method\",\n    \"expects\": {\n      \"@id\": \"hydra:expects\",\n      \"@type\": \"@id\"\n    },\n    \"returns\": {\n      \"@id\": \"hydra:returns\",\n      \"@type\": \"@id\"\n    },\n    \"member\": {\n      \"@id\": \"hydra:member\",\n      \"@container\": \"@list\"\n    },\n    \"totalItems\": {\n      \"@id\": \"hydra:totalItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restful-services/refs/heads/main/json-ld/restful-services-context.jsonld
tags:
- Architecture
- HTTP
- Microservices
- REST
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
