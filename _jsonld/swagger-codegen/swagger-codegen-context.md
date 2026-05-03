---
api_specs:
- filename: swagger-generator-openapi.yml
  format: yaml
  label: Swagger Generator API
  slug: swagger-generator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/openapi/swagger-generator-openapi.yml
class_count: 0
classes: []
context_file: json-ld/swagger-codegen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/json-ld/swagger-codegen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Swagger Codegen from Swagger Codegen.
layout: jsonld
name: Swagger Codegen Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: codegen
  uri: https://api-evangelist.github.io/swagger-codegen/vocab#
properties:
- container: ''
  name: CodeGenerator
  type: reference
- container: ''
  name: GenerationRequest
  type: reference
- container: ''
  name: GeneratorLanguage
  type: reference
- container: ''
  name: GeneratorOption
  type: reference
- container: ''
  name: ClientSdk
  type: reference
- container: ''
  name: ServerStub
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: programmingLanguage
  type: ''
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: version
  type: ''
- container: ''
  name: softwareVersion
  type: ''
- container: ''
  name: featureList
  type: ''
- container: ''
  name: generatorType
  type: ''
- container: ''
  name: codegenVersion
  type: ''
- container: ''
  name: lang
  type: ''
- container: ''
  name: specURL
  type: reference
- container: ''
  name: packageName
  type: ''
- container: ''
  name: packageVersion
  type: ''
- container: ''
  name: groupId
  type: ''
- container: ''
  name: artifactId
  type: ''
- container: ''
  name: modelPackage
  type: ''
- container: ''
  name: apiPackage
  type: ''
- container: ''
  name: templateEngine
  type: ''
- container: list
  name: supportedLanguages
  type: ''
property_count: 27
provider_name: Swagger Codegen
provider_slug: swagger-codegen
slug: swagger-codegen-context
source_filename: swagger-codegen-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"codegen\": \"https://api-evangelist.github.io/swagger-codegen/vocab#\",\n\n    \"CodeGenerator\": {\n      \"@id\": \"codegen:CodeGenerator\",\n      \"@type\": \"@id\"\n    },\n    \"GenerationRequest\": {\n      \"@id\": \"codegen:GenerationRequest\",\n      \"@type\": \"@id\"\n    },\n    \"GeneratorLanguage\": {\n      \"@id\": \"codegen:GeneratorLanguage\",\n      \"@type\": \"@id\"\n    },\n    \"GeneratorOption\": {\n      \"@id\": \"codegen:GeneratorOption\",\n      \"@type\": \"@id\"\n    },\n    \"ClientSdk\": {\n      \"@id\": \"codegen:ClientSdk\",\n      \"@type\": \"@id\"\n    },\n    \"ServerStub\": {\n      \"@id\": \"codegen:ServerStub\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"programmingLanguage\"\
  : { \"@id\": \"schema:programmingLanguage\" },\n    \"codeRepository\": { \"@id\": \"schema:codeRepository\", \"@type\": \"@id\" },\n    \"license\": { \"@id\": \"schema:license\", \"@type\": \"@id\" },\n    \"version\": { \"@id\": \"schema:version\" },\n    \"softwareVersion\": { \"@id\": \"schema:softwareVersion\" },\n    \"featureList\": { \"@id\": \"schema:featureList\" },\n\n    \"generatorType\": { \"@id\": \"codegen:generatorType\" },\n    \"codegenVersion\": { \"@id\": \"codegen:codegenVersion\" },\n    \"lang\": { \"@id\": \"codegen:lang\" },\n    \"specURL\": { \"@id\": \"codegen:specURL\", \"@type\": \"@id\" },\n    \"packageName\": { \"@id\": \"codegen:packageName\" },\n    \"packageVersion\": { \"@id\": \"codegen:packageVersion\" },\n    \"groupId\": { \"@id\": \"codegen:groupId\" },\n    \"artifactId\": { \"@id\": \"codegen:artifactId\" },\n    \"modelPackage\": { \"@id\": \"codegen:modelPackage\" },\n    \"apiPackage\": { \"@id\": \"codegen:apiPackage\" },\n    \"templateEngine\"\
  : { \"@id\": \"codegen:templateEngine\" },\n    \"supportedLanguages\": {\n      \"@id\": \"codegen:supportedLanguages\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/swagger-codegen/refs/heads/main/json-ld/swagger-codegen-context.jsonld
tags:
- Client Libraries
- Code Generation
- Open Source
- OpenAPI
- SDK
- JSON-LD
- Linked Data
- Semantic Web
---
