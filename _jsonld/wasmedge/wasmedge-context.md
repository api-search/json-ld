---
class_count: 10
classes:
- WasmEdgeRuntime
- WasmModule
- WasmFunction
- Plugin
- HostFunction
- Configuration
- AoTCompiler
- Store
- VM
- Executor
context_file: json-ld/wasmedge-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wasmedge/refs/heads/main/json-ld/wasmedge-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wasmedge from WasmEdge.
layout: jsonld
name: Wasmedge Context
namespaces:
- prefix: wasmedge
  uri: https://wasmedge.org/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: wasm
  uri: https://webassembly.github.io/spec/core/vocab#
- prefix: cncf
  uri: https://cncf.io/vocab#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: license
  type: ''
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: optLevel
  type: string
- container: ''
  name: maxMemoryPage
  type: integer
- container: ''
  name: pluginName
  type: string
- container: ''
  name: wasiNn
  type: ''
- container: ''
  name: wasiCrypto
  type: ''
- container: ''
  name: language
  type: ''
- container: ''
  name: runtime
  type: ''
- container: ''
  name: operatingSystem
  type: ''
- container: list
  name: supportedPlatforms
  type: ''
property_count: 14
provider_name: WasmEdge
provider_slug: wasmedge
slug: wasmedge-context
source_filename: wasmedge-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wasmedge\": \"https://wasmedge.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"wasm\": \"https://webassembly.github.io/spec/core/vocab#\",\n    \"cncf\": \"https://cncf.io/vocab#\",\n\n    \"WasmEdgeRuntime\": \"wasmedge:WasmEdgeRuntime\",\n    \"WasmModule\": \"wasmedge:WasmModule\",\n    \"WasmFunction\": \"wasmedge:WasmFunction\",\n    \"Plugin\": \"wasmedge:Plugin\",\n    \"HostFunction\": \"wasmedge:HostFunction\",\n    \"Configuration\": \"wasmedge:Configuration\",\n    \"AoTCompiler\": \"wasmedge:AoTCompiler\",\n    \"Store\": \"wasmedge:Store\",\n    \"VM\": \"wasmedge:VM\",\n    \"Executor\": \"wasmedge:Executor\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\"\n    },\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n\n    \"optLevel\": {\n      \"@id\": \"wasmedge:optLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxMemoryPage\": {\n      \"@id\": \"wasmedge:maxMemoryPage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pluginName\": {\n      \"@id\": \"wasmedge:pluginName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wasiNn\": {\n      \"@id\": \"wasmedge:wasiNn\"\n    },\n    \"wasiCrypto\": {\n      \"@id\": \"wasmedge:wasiCrypto\"\n    },\n    \"language\": {\n      \"@id\": \"schema:programmingLanguage\"\n    },\n    \"runtime\": {\n      \"@id\": \"schema:runtimePlatform\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"schema:operatingSystem\"\n    },\n    \"supportedPlatforms\": {\n      \"\
  @id\": \"wasmedge:supportedPlatforms\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wasmedge/refs/heads/main/json-ld/wasmedge-context.jsonld
tags:
- Cloud Native
- CNCF
- Edge Computing
- High Performance
- Runtime
- Serverless
- Wasm
- WebAssembly
- JSON-LD
- Linked Data
- Semantic Web
---
