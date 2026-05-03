---
class_count: 15
classes:
- RAMLDocument
- Resource
- Method
- TypeDeclaration
- Trait
- ResourceType
- SecurityScheme
- AnnotationType
- Library
- title
- description
- example
- examples
- displayName
- uriParameters
context_file: json-ld/raml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/raml/refs/heads/main/json-ld/raml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Raml from RAML.
layout: jsonld
name: Raml Context
namespaces:
- prefix: raml
  uri: https://raml.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
properties:
- container: ''
  name: version
  type: ''
- container: ''
  name: baseUri
  type: anyURI
- container: list
  name: protocols
  type: ''
- container: ''
  name: mediaType
  type: ''
- container: ''
  name: types
  type: reference
- container: ''
  name: traits
  type: reference
- container: ''
  name: resourceTypes
  type: reference
- container: ''
  name: securitySchemes
  type: reference
- container: ''
  name: annotationTypes
  type: reference
- container: list
  name: securedBy
  type: ''
- container: ''
  name: uses
  type: reference
- container: ''
  name: queryParameters
  type: ''
- container: ''
  name: headers
  type: ''
- container: ''
  name: body
  type: ''
- container: ''
  name: responses
  type: ''
- container: ''
  name: properties
  type: ''
- container: ''
  name: required
  type: boolean
- container: list
  name: is
  type: ''
property_count: 18
provider_name: RAML
provider_slug: raml
slug: raml-context
source_filename: raml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"raml\": \"https://raml.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n\n    \"RAMLDocument\": \"raml:Document\",\n    \"Resource\": \"raml:Resource\",\n    \"Method\": \"raml:Method\",\n    \"TypeDeclaration\": \"raml:TypeDeclaration\",\n    \"Trait\": \"raml:Trait\",\n    \"ResourceType\": \"raml:ResourceType\",\n    \"SecurityScheme\": \"raml:SecurityScheme\",\n    \"AnnotationType\": \"raml:AnnotationType\",\n    \"Library\": \"raml:Library\",\n\n    \"title\": \"dcterms:title\",\n    \"description\": \"dcterms:description\",\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"baseUri\": {\n      \"@id\": \"raml:baseUri\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"protocols\": {\n      \"@id\": \"raml:protocols\",\n      \"@container\":\
  \ \"@list\"\n    },\n    \"mediaType\": {\n      \"@id\": \"raml:mediaType\"\n    },\n    \"types\": {\n      \"@id\": \"raml:types\",\n      \"@type\": \"@id\"\n    },\n    \"traits\": {\n      \"@id\": \"raml:traits\",\n      \"@type\": \"@id\"\n    },\n    \"resourceTypes\": {\n      \"@id\": \"raml:resourceTypes\",\n      \"@type\": \"@id\"\n    },\n    \"securitySchemes\": {\n      \"@id\": \"raml:securitySchemes\",\n      \"@type\": \"@id\"\n    },\n    \"annotationTypes\": {\n      \"@id\": \"raml:annotationTypes\",\n      \"@type\": \"@id\"\n    },\n    \"securedBy\": {\n      \"@id\": \"raml:securedBy\",\n      \"@container\": \"@list\"\n    },\n    \"uses\": {\n      \"@id\": \"raml:uses\",\n      \"@type\": \"@id\"\n    },\n    \"queryParameters\": {\n      \"@id\": \"raml:queryParameters\"\n    },\n    \"headers\": {\n      \"@id\": \"raml:headers\"\n    },\n    \"body\": {\n      \"@id\": \"raml:body\"\n    },\n    \"responses\": {\n      \"@id\": \"raml:responses\"\n    },\n\
  \    \"properties\": {\n      \"@id\": \"raml:properties\"\n    },\n    \"required\": {\n      \"@id\": \"raml:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"example\": \"raml:example\",\n    \"examples\": \"raml:examples\",\n    \"displayName\": \"raml:displayName\",\n    \"uriParameters\": \"raml:uriParameters\",\n    \"is\": {\n      \"@id\": \"raml:appliedTraits\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/raml/refs/heads/main/json-ld/raml-context.jsonld
tags:
- API Design
- Specification Language
- Standards
- YAML
- REST
- API Modeling
- JSON-LD
- Linked Data
- Semantic Web
---
