---
class_count: 9
classes:
- name
- description
- url
- version
- SoftwareApplication
- SoftwareSourceCode
- codeRepository
- programmingLanguage
- license
context_file: json-ld/refitter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/refitter/refs/heads/main/json-ld/refitter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Refitter from Refitter.
layout: jsonld
name: Refitter Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: refitter
  uri: https://refitter.github.io/vocabulary#
properties:
- container: ''
  name: CodeGenerator
  type: ''
- container: ''
  name: SourceGenerator
  type: ''
- container: ''
  name: RefitInterface
  type: ''
- container: ''
  name: openApiSpec
  type: reference
- container: ''
  name: generatedNamespace
  type: string
- container: ''
  name: outputFile
  type: string
- container: ''
  name: typeStyle
  type: string
property_count: 7
provider_name: Refitter
provider_slug: refitter
slug: refitter-context
source_filename: refitter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"refitter\": \"https://refitter.github.io/vocabulary#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"license\": \"schema:license\",\n    \"CodeGenerator\": {\n      \"@id\": \"refitter:CodeGenerator\",\n      \"description\": \"A tool that generates source code from a specification.\"\n    },\n    \"SourceGenerator\": {\n      \"@id\": \"refitter:SourceGenerator\",\n      \"description\": \"A .NET Roslyn source generator that produces code at compile time.\"\n    },\n    \"RefitInterface\"\
  : {\n      \"@id\": \"refitter:RefitInterface\",\n      \"description\": \"A C# interface decorated with Refit attributes, generated from an OpenAPI spec.\"\n    },\n    \"openApiSpec\": {\n      \"@id\": \"refitter:openApiSpec\",\n      \"@type\": \"@id\",\n      \"description\": \"The OpenAPI specification input to the code generator.\"\n    },\n    \"generatedNamespace\": {\n      \"@id\": \"refitter:generatedNamespace\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"The C# namespace for generated code.\"\n    },\n    \"outputFile\": {\n      \"@id\": \"refitter:outputFile\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"The file path for generated output.\"\n    },\n    \"typeStyle\": {\n      \"@id\": \"refitter:typeStyle\",\n      \"@type\": \"xsd:string\",\n      \"description\": \"The C# code style for generated types (Classes, Records, or RecordsStruct).\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/refitter/refs/heads/main/json-ld/refitter-context.jsonld
tags:
- .NET
- C#
- Code Generation
- OpenAPI
- Refit
- Source Generator
- Type-Safe
- JSON-LD
- Linked Data
- Semantic Web
---
