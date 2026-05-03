---
class_count: 3
classes:
- SpinApplication
- SpinComponent
- SpinVariable
context_file: json-ld/spin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spin/refs/heads/main/json-ld/spin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spin from Spin.
layout: jsonld
name: Spin Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spin
  uri: https://spinframework.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: spin_manifest_version
  type: integer
- container: ''
  name: application
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: description
  type: string
- container: list
  name: authors
  type: ''
- container: ''
  name: component
  type: reference
- container: ''
  name: source
  type: string
- container: list
  name: allowed_outbound_hosts
  type: ''
- container: list
  name: key_value_stores
  type: ''
- container: list
  name: sqlite_databases
  type: ''
- container: list
  name: ai_models
  type: ''
- container: ''
  name: variables
  type: reference
- container: ''
  name: required
  type: boolean
- container: ''
  name: secret
  type: boolean
property_count: 15
provider_name: Spin
provider_slug: spin
slug: spin-context
source_filename: spin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spin\": \"https://spinframework.dev/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SpinApplication\": \"spin:Application\",\n    \"SpinComponent\": \"spin:Component\",\n    \"SpinVariable\": \"spin:Variable\",\n\n    \"spin_manifest_version\": {\n      \"@id\": \"spin:manifestVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"application\": {\n      \"@id\": \"spin:application\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authors\": {\n      \"@id\": \"schema:author\",\n      \"@container\": \"@list\"\n    },\n    \"component\": {\n      \"@id\": \"spin:component\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"source\": {\n      \"@id\": \"spin:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed_outbound_hosts\": {\n      \"@id\": \"spin:allowedOutboundHosts\",\n      \"@container\": \"@list\"\n    },\n    \"key_value_stores\": {\n      \"@id\": \"spin:keyValueStores\",\n      \"@container\": \"@list\"\n    },\n    \"sqlite_databases\": {\n      \"@id\": \"spin:sqliteDatabases\",\n      \"@container\": \"@list\"\n    },\n    \"ai_models\": {\n      \"@id\": \"spin:aiModels\",\n      \"@container\": \"@list\"\n    },\n    \"variables\": {\n      \"@id\": \"spin:variables\",\n      \"@type\": \"@id\"\n    },\n    \"required\": {\n      \"@id\": \"spin:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"secret\": {\n      \"@id\": \"spin:secret\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spin/refs/heads/main/json-ld/spin-context.jsonld
tags:
- Cloud Native
- Microservices
- Serverless
- WebAssembly
- JSON-LD
- Linked Data
- Semantic Web
---
