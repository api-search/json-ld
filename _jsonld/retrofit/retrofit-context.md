---
class_count: 11
classes:
- Library
- HttpClient
- Converter
- CallAdapter
- ServiceInterface
- name
- description
- version
- programmingLanguage
- targetPlatform
- softwareRequirements
context_file: json-ld/retrofit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/json-ld/retrofit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Retrofit from Retrofit.
layout: jsonld
name: Retrofit Context
namespaces:
- prefix: retrofit
  uri: https://square.github.io/retrofit/ns/
- prefix: http
  uri: http://www.w3.org/2011/http#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: license
  type: reference
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: releaseNotes
  type: reference
- container: ''
  name: author
  type: reference
property_count: 4
provider_name: Retrofit
provider_slug: retrofit
slug: retrofit-context
source_filename: retrofit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"retrofit\": \"https://square.github.io/retrofit/ns/\",\n    \"http\": \"http://www.w3.org/2011/http#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Library\": \"schema:SoftwareSourceCode\",\n    \"HttpClient\": \"retrofit:HttpClient\",\n    \"Converter\": \"retrofit:Converter\",\n    \"CallAdapter\": \"retrofit:CallAdapter\",\n    \"ServiceInterface\": \"retrofit:ServiceInterface\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"releaseNotes\": {\n      \"@id\": \"schema:releaseNotes\",\n      \"@type\": \"@id\"\
  \n    },\n    \"targetPlatform\": \"schema:targetPlatform\",\n    \"softwareRequirements\": \"schema:softwareRequirements\",\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/retrofit/refs/heads/main/json-ld/retrofit-context.jsonld
tags:
- Android
- HTTP Client
- Java
- Kotlin
- Library
- Mobile
- Open Source
- SDK
- Square
- JSON-LD
- Linked Data
- Semantic Web
---
