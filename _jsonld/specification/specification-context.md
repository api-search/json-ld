---
class_count: 6
classes:
- name
- description
- url
- version
- TechArticle
- SoftwareApplication
context_file: json-ld/specification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/specification/refs/heads/main/json-ld/specification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Specification from Specification.
layout: jsonld
name: Specification Context
namespaces:
- prefix: spec
  uri: https://api-evangelist.com/vocab/specification/
- prefix: oas
  uri: https://spec.openapis.org/oas/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: APISpecification
  type: reference
- container: ''
  name: OpenAPISpec
  type: reference
- container: ''
  name: AsyncAPISpec
  type: reference
- container: ''
  name: JSONSchemaSpec
  type: reference
- container: ''
  name: ArazzoSpec
  type: reference
- container: ''
  name: specFormat
  type: string
- container: ''
  name: specVersion
  type: string
- container: ''
  name: baseUrl
  type: anyURI
- container: ''
  name: paths
  type: integer
- container: ''
  name: schemas
  type: integer
- container: ''
  name: maintainer
  type: reference
property_count: 11
provider_name: Specification
provider_slug: specification
slug: specification-context
source_filename: specification-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spec\": \"https://api-evangelist.com/vocab/specification/\",\n    \"oas\": \"https://spec.openapis.org/oas/vocab/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"version\": \"version\",\n    \"TechArticle\": \"TechArticle\",\n    \"SoftwareApplication\": \"SoftwareApplication\",\n    \"APISpecification\": {\n      \"@id\": \"spec:APISpecification\",\n      \"@type\": \"@id\"\n    },\n    \"OpenAPISpec\": {\n      \"@id\": \"spec:OpenAPISpec\",\n      \"@type\": \"@id\"\n    },\n    \"AsyncAPISpec\": {\n      \"@id\": \"spec:AsyncAPISpec\",\n      \"@type\": \"@id\"\n    },\n    \"JSONSchemaSpec\": {\n      \"@id\": \"spec:JSONSchemaSpec\",\n      \"@type\": \"@id\"\n    },\n    \"ArazzoSpec\": {\n      \"@id\": \"spec:ArazzoSpec\",\n      \"@type\": \"@id\"\n    },\n    \"specFormat\": {\n      \"@id\": \"spec:format\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"specVersion\": {\n      \"@id\": \"spec:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"spec:baseUrl\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"paths\": {\n      \"@id\": \"spec:paths\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"schemas\": {\n      \"@id\": \"spec:schemas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maintainer\": {\n      \"@id\": \"spec:maintainer\",\n      \"@type\": \"@id\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/specification/refs/heads/main/json-ld/specification-context.jsonld
tags:
- API Design
- API Governance
- AsyncAPI
- Contract Testing
- JSON Schema
- OpenAPI
- Specifications
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
