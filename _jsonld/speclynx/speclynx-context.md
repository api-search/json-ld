---
class_count: 5
classes:
- name
- description
- url
- SoftwareApplication
- SoftwareSourceCode
context_file: json-ld/speclynx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/speclynx/refs/heads/main/json-ld/speclynx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Speclynx from SpecLynx.
layout: jsonld
name: Speclynx Context
namespaces:
- prefix: speclynx
  uri: https://speclynx.com/vocab/
- prefix: lsp
  uri: https://microsoft.github.io/language-server-protocol/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: OpenAPIToolkit
  type: reference
- container: ''
  name: LanguageService
  type: reference
- container: ''
  name: ApiDOM
  type: reference
- container: ''
  name: ValidationResult
  type: reference
- container: ''
  name: CompletionItem
  type: reference
- container: ''
  name: severity
  type: string
- container: ''
  name: specificationFormat
  type: string
- container: ''
  name: diagnosticCode
  type: string
- container: ''
  name: validationSource
  type: string
- container: ''
  name: insertText
  type: string
- container: ''
  name: range
  type: reference
property_count: 11
provider_name: SpecLynx
provider_slug: speclynx
slug: speclynx-context
source_filename: speclynx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"speclynx\": \"https://speclynx.com/vocab/\",\n    \"lsp\": \"https://microsoft.github.io/language-server-protocol/vocab/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"SoftwareApplication\": \"SoftwareApplication\",\n    \"SoftwareSourceCode\": \"SoftwareSourceCode\",\n    \"OpenAPIToolkit\": {\n      \"@id\": \"speclynx:OpenAPIToolkit\",\n      \"@type\": \"@id\"\n    },\n    \"LanguageService\": {\n      \"@id\": \"speclynx:LanguageService\",\n      \"@type\": \"@id\"\n    },\n    \"ApiDOM\": {\n      \"@id\": \"speclynx:ApiDOM\",\n      \"@type\": \"@id\"\n    },\n    \"ValidationResult\": {\n      \"@id\": \"speclynx:ValidationResult\",\n      \"@type\": \"@id\"\n    },\n    \"CompletionItem\": {\n      \"@id\": \"lsp:CompletionItem\",\n      \"@type\": \"@id\"\n    },\n    \"severity\": {\n      \"@id\": \"speclynx:severity\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"specificationFormat\": {\n      \"@id\": \"speclynx:specificationFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diagnosticCode\": {\n      \"@id\": \"speclynx:diagnosticCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationSource\": {\n      \"@id\": \"speclynx:validationSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insertText\": {\n      \"@id\": \"lsp:insertText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"range\": {\n      \"@id\": \"lsp:Range\",\n      \"@type\": \"@id\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/speclynx/refs/heads/main/json-ld/speclynx-context.jsonld
tags:
- API Design
- AsyncAPI
- Developer Tools
- JSON Schema
- OpenAPI
- Toolkit
- VSCode
- JSON-LD
- Linked Data
- Semantic Web
---
