---
class_count: 15
classes:
- TypeSpecProgram
- TypeSpecNamespace
- TypeSpecModel
- TypeSpecInterface
- TypeSpecOperation
- TypeSpecEnum
- TypeSpecScalar
- TypeSpecDecorator
- TypeSpecEmitter
- TypeSpecLibrary
- SoftwareApplication
- name
- description
- version
- url
context_file: json-ld/typespec-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/typespec/refs/heads/main/json-ld/typespec-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Typespec from TypeSpec.
layout: jsonld
name: Typespec Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tsp
  uri: https://typespec.io/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: namespaceName
  type: string
- container: ''
  name: modelName
  type: string
- container: ''
  name: operationName
  type: string
- container: ''
  name: decoratorName
  type: string
- container: ''
  name: emitterTarget
  type: string
- container: ''
  name: hasProperty
  type: reference
- container: ''
  name: hasOperation
  type: reference
- container: ''
  name: extendsModel
  type: reference
- container: ''
  name: httpMethod
  type: string
- container: ''
  name: httpRoute
  type: string
- container: ''
  name: isOptional
  type: boolean
property_count: 11
provider_name: TypeSpec
provider_slug: typespec
slug: typespec-context
source_filename: typespec-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tsp\": \"https://typespec.io/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TypeSpecProgram\": \"tsp:TypeSpecProgram\",\n    \"TypeSpecNamespace\": \"tsp:TypeSpecNamespace\",\n    \"TypeSpecModel\": \"tsp:TypeSpecModel\",\n    \"TypeSpecInterface\": \"tsp:TypeSpecInterface\",\n    \"TypeSpecOperation\": \"tsp:TypeSpecOperation\",\n    \"TypeSpecEnum\": \"tsp:TypeSpecEnum\",\n    \"TypeSpecScalar\": \"tsp:TypeSpecScalar\",\n    \"TypeSpecDecorator\": \"tsp:TypeSpecDecorator\",\n    \"TypeSpecEmitter\": \"tsp:TypeSpecEmitter\",\n    \"TypeSpecLibrary\": \"tsp:TypeSpecLibrary\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n\n    \"namespaceName\": {\n      \"@id\": \"tsp:namespaceName\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"modelName\": {\n      \"@id\": \"tsp:modelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationName\": {\n      \"@id\": \"tsp:operationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decoratorName\": {\n      \"@id\": \"tsp:decoratorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emitterTarget\": {\n      \"@id\": \"tsp:emitterTarget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasProperty\": {\n      \"@id\": \"tsp:hasProperty\",\n      \"@type\": \"@id\"\n    },\n    \"hasOperation\": {\n      \"@id\": \"tsp:hasOperation\",\n      \"@type\": \"@id\"\n    },\n    \"extendsModel\": {\n      \"@id\": \"tsp:extendsModel\",\n      \"@type\": \"@id\"\n    },\n    \"httpMethod\": {\n      \"@id\": \"tsp:httpMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpRoute\": {\n      \"@id\": \"tsp:httpRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isOptional\": {\n      \"@id\": \"tsp:isOptional\",\n\
  \      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/typespec/refs/heads/main/json-ld/typespec-context.jsonld
tags:
- API Design
- Code Generation
- OpenAPI
- Protocol Buffers
- Specification Language
- JSON-LD
- Linked Data
- Semantic Web
---
