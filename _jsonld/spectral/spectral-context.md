---
class_count: 9
classes:
- name
- description
- url
- version
- dateCreated
- dateModified
- SoftwareApplication
- SoftwareSourceCode
- programmingLanguage
context_file: json-ld/spectral-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spectral/refs/heads/main/json-ld/spectral-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spectral from Spectral.
layout: jsonld
name: Spectral Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spectral
  uri: https://stoplight.io/spectral/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Ruleset
  type: reference
- container: ''
  name: Rule
  type: reference
- container: ''
  name: LintingResult
  type: reference
- container: ''
  name: Violation
  type: reference
- container: ''
  name: given
  type: string
- container: ''
  name: severity
  type: '@vocab'
- container: ''
  name: message
  type: string
- container: ''
  name: functionName
  type: string
- container: ''
  name: format
  type: '@vocab'
- container: ''
  name: recommended
  type: boolean
property_count: 10
provider_name: Spectral
provider_slug: spectral
slug: spectral-context
source_filename: spectral-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spectral\": \"https://stoplight.io/spectral/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Ruleset\": {\n      \"@id\": \"spectral:Ruleset\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A Spectral configuration defining linting rules for API specifications.\"\n    },\n    \"Rule\": {\n      \"@id\": \"spectral:Rule\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"An individual linting check within a Spectral ruleset.\"\n    },\n    \"LintingResult\": {\n      \"@id\": \"spectral:LintingResult\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"The output of running Spectral against a document.\"\n    },\n    \"Violation\": {\n      \"@id\": \"spectral:Violation\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A rule violation found during linting.\"\n    },\n\n    \"given\": {\n      \"@id\": \"spectral:given\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"spectral:severity\",\n      \"@type\": \"@vocab\"\n    },\n    \"message\": {\n      \"@id\": \"spectral:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionName\": {\n      \"@id\": \"spectral:functionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"spectral:format\",\n      \"@type\": \"@vocab\"\n    },\n    \"recommended\": {\n      \"@id\": \"spectral:recommended\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"programmingLanguage\": \"schema:programmingLanguage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spectral/refs/heads/main/json-ld/spectral-context.jsonld
tags:
- API Design
- API Linting
- API Style Guide
- AsyncAPI
- JSON Schema
- OpenAPI
- Quality Assurance
- JSON-LD
- Linked Data
- Semantic Web
---
