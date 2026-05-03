---
class_count: 25
classes:
- RestClient
- RestRequest
- RestResponse
- RestClientOptions
- Parameter
- name
- description
- version
- url
- license
- programmingLanguage
- runtimePlatform
- releaseNotes
- author
- maintainer
- baseUrl
- resource
- method
- timeout
- authenticator
- requestFormat
- statusCode
- isSuccessful
- errorMessage
- content
context_file: json-ld/restsharp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restsharp/refs/heads/main/json-ld/restsharp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restsharp from RestSharp.
layout: jsonld
name: Restsharp Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: restsharp
  uri: https://restsharp.dev/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: codemeta
  uri: https://codemeta.github.io/terms/
properties:
- container: ''
  name: codeRepository
  type: reference
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: datePublished
  type: date
- container: list
  name: parameters
  type: ''
property_count: 4
provider_name: RestSharp
provider_slug: restsharp
slug: restsharp-context
source_filename: restsharp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"restsharp\": \"https://restsharp.dev/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"codemeta\": \"https://codemeta.github.io/terms/\",\n\n    \"RestClient\": \"restsharp:RestClient\",\n    \"RestRequest\": \"restsharp:RestRequest\",\n    \"RestResponse\": \"restsharp:RestResponse\",\n    \"RestClientOptions\": \"restsharp:RestClientOptions\",\n    \"Parameter\": \"restsharp:Parameter\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"url\": \"schema:url\",\n    \"license\": \"schema:license\",\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    },\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"runtimePlatform\": \"schema:runtimePlatform\",\n    \"downloadUrl\": {\n      \"@id\": \"schema:downloadUrl\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"releaseNotes\": \"schema:releaseNotes\",\n    \"datePublished\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"author\": \"schema:author\",\n    \"maintainer\": \"schema:maintainer\",\n\n    \"baseUrl\": \"restsharp:baseUrl\",\n    \"resource\": \"restsharp:resource\",\n    \"method\": \"restsharp:httpMethod\",\n    \"timeout\": \"restsharp:timeout\",\n    \"authenticator\": \"restsharp:authenticator\",\n    \"parameters\": {\n      \"@id\": \"restsharp:parameters\",\n      \"@container\": \"@list\"\n    },\n    \"requestFormat\": \"restsharp:requestFormat\",\n    \"statusCode\": \"restsharp:statusCode\",\n    \"isSuccessful\": \"restsharp:isSuccessful\",\n    \"errorMessage\": \"restsharp:errorMessage\",\n    \"content\": \"restsharp:content\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restsharp/refs/heads/main/json-ld/restsharp-context.jsonld
tags:
- .NET
- Apache License
- C#
- HTTP Client
- NuGet
- Open Source
- SDKs
- JSON-LD
- Linked Data
- Semantic Web
---
