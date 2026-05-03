---
class_count: 0
classes: []
context_file: json-ld/relay-compiler-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/json-ld/relay-compiler-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Relay Compiler from Relay Compiler.
layout: jsonld
name: Relay Compiler Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: relay
  uri: https://relay.dev/vocab/
properties:
- container: ''
  name: SoftwareSourceCode
  type: ''
- container: ''
  name: GraphQLSchema
  type: reference
- container: ''
  name: Fragment
  type: reference
- container: ''
  name: Query
  type: reference
- container: ''
  name: Mutation
  type: reference
- container: ''
  name: Subscription
  type: reference
- container: ''
  name: CompilerArtifact
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: language
  type: ''
- container: ''
  name: schemaFile
  type: ''
- container: ''
  name: fragmentName
  type: ''
- container: ''
  name: 'on'
  type: ''
- container: ''
  name: directive
  type: ''
- container: ''
  name: argument
  type: ''
- container: ''
  name: outputType
  type: ''
- container: ''
  name: typegenEnabled
  type: boolean
- container: ''
  name: license
  type: ''
- container: ''
  name: codeRepository
  type: ''
property_count: 20
provider_name: Relay Compiler
provider_slug: relay-compiler
slug: relay-compiler-context
source_filename: relay-compiler-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"relay\": \"https://relay.dev/vocab/\",\n    \"SoftwareSourceCode\": {\n      \"@id\": \"schema:SoftwareSourceCode\"\n    },\n    \"GraphQLSchema\": {\n      \"@id\": \"relay:GraphQLSchema\",\n      \"@type\": \"@id\"\n    },\n    \"Fragment\": {\n      \"@id\": \"relay:Fragment\",\n      \"@type\": \"@id\"\n    },\n    \"Query\": {\n      \"@id\": \"relay:Query\",\n      \"@type\": \"@id\"\n    },\n    \"Mutation\": {\n      \"@id\": \"relay:Mutation\",\n      \"@type\": \"@id\"\n    },\n    \"Subscription\": {\n      \"@id\": \"relay:Subscription\",\n      \"@type\": \"@id\"\n    },\n    \"CompilerArtifact\": {\n      \"@id\": \"relay:CompilerArtifact\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"version\"\
  : {\n      \"@id\": \"schema:version\"\n    },\n    \"language\": {\n      \"@id\": \"schema:programmingLanguage\"\n    },\n    \"schemaFile\": {\n      \"@id\": \"relay:schemaFile\"\n    },\n    \"fragmentName\": {\n      \"@id\": \"relay:fragmentName\"\n    },\n    \"on\": {\n      \"@id\": \"relay:onType\"\n    },\n    \"directive\": {\n      \"@id\": \"relay:directive\"\n    },\n    \"argument\": {\n      \"@id\": \"relay:argument\"\n    },\n    \"outputType\": {\n      \"@id\": \"relay:outputType\"\n    },\n    \"typegenEnabled\": {\n      \"@id\": \"relay:typegenEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"language\": {\n      \"@id\": \"relay:typeLanguage\"\n    },\n    \"license\": {\n      \"@id\": \"schema:license\"\n    },\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/relay-compiler/refs/heads/main/json-ld/relay-compiler-context.jsonld
tags:
- Code Generation
- GraphQL
- React
- Meta
- Open Source
- TypeScript
- Build Tools
- JSON-LD
- Linked Data
- Semantic Web
---
