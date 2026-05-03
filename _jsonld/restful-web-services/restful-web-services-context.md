---
class_count: 13
classes:
- WebService
- Collection
- PaginatedCollection
- Software
- Framework
- id
- type
- name
- description
- version
- programmingLanguage
- license
- softwareRequirements
context_file: json-ld/restful-web-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restful-web-services/refs/heads/main/json-ld/restful-web-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restful Web Services from RESTful Web Services.
layout: jsonld
name: Restful Web Services Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rws
  uri: https://api-evangelist.github.io/restful-web-services/vocab/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: documentation
  type: reference
- container: list
  name: data
  type: ''
- container: ''
  name: totalItems
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: perPage
  type: integer
- container: ''
  name: hasMore
  type: boolean
- container: ''
  name: links
  type: reference
- container: ''
  name: next
  type: reference
- container: ''
  name: prev
  type: reference
- container: ''
  name: first
  type: reference
- container: ''
  name: last
  type: reference
- container: ''
  name: self
  type: reference
property_count: 14
provider_name: RESTful Web Services
provider_slug: restful-web-services
slug: restful-web-services-context
source_filename: restful-web-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rws\": \"https://api-evangelist.github.io/restful-web-services/vocab/\",\n\n    \"WebService\": \"schema:WebAPI\",\n    \"Collection\": \"hydra:Collection\",\n    \"PaginatedCollection\": \"rws:PaginatedCollection\",\n    \"Software\": \"schema:SoftwareApplication\",\n    \"Framework\": \"schema:SoftwareApplication\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"documentation\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"schema:version\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"\
  license\": \"schema:license\",\n    \"softwareRequirements\": \"schema:softwareRequirements\",\n\n    \"data\": {\n      \"@id\": \"hydra:member\",\n      \"@container\": \"@list\"\n    },\n    \"totalItems\": {\n      \"@id\": \"hydra:totalItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"rws:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"rws:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perPage\": {\n      \"@id\": \"hydra:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hasMore\": {\n      \"@id\": \"rws:hasMore\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"links\": {\n      \"@id\": \"rws:links\",\n      \"@type\": \"@id\"\n    },\n    \"next\": {\n      \"@id\": \"hydra:next\",\n      \"@type\": \"@id\"\n    },\n    \"prev\": {\n      \"@id\": \"hydra:previous\",\n      \"@type\": \"@id\"\n    },\n    \"first\": {\n      \"@id\": \"hydra:first\",\n      \"@type\": \"@id\"\
  \n    },\n    \"last\": {\n      \"@id\": \"hydra:last\",\n      \"@type\": \"@id\"\n    },\n    \"self\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restful-web-services/refs/heads/main/json-ld/restful-web-services-context.jsonld
tags:
- Architecture
- HTTP
- REST
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
