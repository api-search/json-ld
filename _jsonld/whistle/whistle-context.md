---
class_count: 9
classes:
- name
- description
- url
- version
- SoftwareApplication
- operatingSystem
- softwareRequirements
- applicationCategory
- downloadUrl
context_file: json-ld/whistle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whistle/refs/heads/main/json-ld/whistle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whistle from Whistle.
layout: jsonld
name: Whistle Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: whistle
  uri: https://wproxy.org/whistle/
properties:
- container: ''
  name: pattern
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: rule
  type: reference
- container: ''
  name: plugin
  type: reference
- container: ''
  name: proxy
  type: reference
- container: ''
  name: port
  type: integer
- container: ''
  name: interceptedRequest
  type: reference
- container: ''
  name: requestHeaders
  type: reference
- container: ''
  name: responseHeaders
  type: reference
- container: ''
  name: requestBody
  type: string
- container: ''
  name: responseBody
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: protocol
  type: string
- container: ''
  name: weinre
  type: reference
- container: ''
  name: composer
  type: reference
property_count: 15
provider_name: Whistle
provider_slug: whistle
slug: whistle-context
source_filename: whistle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"whistle\": \"https://wproxy.org/whistle/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"operatingSystem\": \"schema:operatingSystem\",\n    \"softwareRequirements\": \"schema:softwareRequirements\",\n    \"applicationCategory\": \"schema:applicationCategory\",\n    \"downloadUrl\": \"schema:downloadUrl\",\n    \"pattern\": {\n      \"@id\": \"whistle:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"whistle:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rule\": {\n      \"@id\": \"whistle:rule\",\n      \"@type\": \"@id\"\n    },\n    \"plugin\": {\n      \"@id\": \"whistle:plugin\",\n      \"@type\": \"@id\"\
  \n    },\n    \"proxy\": {\n      \"@id\": \"whistle:proxy\",\n      \"@type\": \"@id\"\n    },\n    \"port\": {\n      \"@id\": \"whistle:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"interceptedRequest\": {\n      \"@id\": \"whistle:interceptedRequest\",\n      \"@type\": \"@id\"\n    },\n    \"requestHeaders\": {\n      \"@id\": \"whistle:requestHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"responseHeaders\": {\n      \"@id\": \"whistle:responseHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"requestBody\": {\n      \"@id\": \"whistle:requestBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseBody\": {\n      \"@id\": \"whistle:responseBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"whistle:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protocol\": {\n      \"@id\": \"whistle:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weinre\": {\n      \"@id\": \"whistle:weinre\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"composer\": {\n      \"@id\": \"whistle:composer\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whistle/refs/heads/main/json-ld/whistle-context.jsonld
tags:
- Debugging Proxy
- Proxy
- Network Debugging
- HTTP
- HTTPS
- WebSocket
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
