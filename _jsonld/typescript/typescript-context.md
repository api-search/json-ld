---
class_count: 15
classes:
- TypeScriptProgram
- TypeScriptFile
- TypeScriptType
- TypeScriptInterface
- TypeScriptClass
- TypeScriptFunction
- TypeScriptModule
- CompilerOptions
- Diagnostic
- SourceFile
- Symbol
- name
- description
- version
- url
context_file: json-ld/typescript-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/typescript/refs/heads/main/json-ld/typescript-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Typescript from TypeScript.
layout: jsonld
name: Typescript Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ts
  uri: https://www.typescriptlang.org/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: fileName
  type: string
- container: ''
  name: typeName
  type: string
- container: ''
  name: isExported
  type: boolean
- container: ''
  name: isOptional
  type: boolean
- container: ''
  name: hasType
  type: reference
- container: ''
  name: hasMember
  type: reference
- container: ''
  name: extends
  type: reference
- container: ''
  name: implements
  type: reference
- container: ''
  name: compilerTarget
  type: string
- container: ''
  name: strictMode
  type: boolean
- container: ''
  name: diagnosticMessage
  type: string
- container: ''
  name: diagnosticCategory
  type: string
- container: ''
  name: lineNumber
  type: integer
property_count: 13
provider_name: TypeScript
provider_slug: typescript
slug: typescript-context
source_filename: typescript-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ts\": \"https://www.typescriptlang.org/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TypeScriptProgram\": \"ts:TypeScriptProgram\",\n    \"TypeScriptFile\": \"ts:TypeScriptFile\",\n    \"TypeScriptType\": \"ts:TypeScriptType\",\n    \"TypeScriptInterface\": \"ts:TypeScriptInterface\",\n    \"TypeScriptClass\": \"ts:TypeScriptClass\",\n    \"TypeScriptFunction\": \"ts:TypeScriptFunction\",\n    \"TypeScriptModule\": \"ts:TypeScriptModule\",\n    \"CompilerOptions\": \"ts:CompilerOptions\",\n    \"Diagnostic\": \"ts:Diagnostic\",\n    \"SourceFile\": \"ts:SourceFile\",\n    \"Symbol\": \"ts:Symbol\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n\n    \"fileName\": {\n      \"@id\": \"ts:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"typeName\"\
  : {\n      \"@id\": \"ts:typeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isExported\": {\n      \"@id\": \"ts:isExported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isOptional\": {\n      \"@id\": \"ts:isOptional\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasType\": {\n      \"@id\": \"ts:hasType\",\n      \"@type\": \"@id\"\n    },\n    \"hasMember\": {\n      \"@id\": \"ts:hasMember\",\n      \"@type\": \"@id\"\n    },\n    \"extends\": {\n      \"@id\": \"ts:extends\",\n      \"@type\": \"@id\"\n    },\n    \"implements\": {\n      \"@id\": \"ts:implements\",\n      \"@type\": \"@id\"\n    },\n    \"compilerTarget\": {\n      \"@id\": \"ts:compilerTarget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strictMode\": {\n      \"@id\": \"ts:strictMode\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"diagnosticMessage\": {\n      \"@id\": \"ts:diagnosticMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diagnosticCategory\": {\n      \"@id\": \"\
  ts:diagnosticCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineNumber\": {\n      \"@id\": \"ts:lineNumber\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/typescript/refs/heads/main/json-ld/typescript-context.jsonld
tags:
- Compiler
- JavaScript
- Language Service
- Programming Language
- Static Typing
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---
