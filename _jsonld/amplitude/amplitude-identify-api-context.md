---
class_count: 5
classes:
- UserPropertyOperations
- Identification
- IdentifyResponse
- IdentifyRequestForm
- IdentifyRequestBody
context_file: json-ld/amplitude-identify-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-identify-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Identify Api from Amplitude.
layout: jsonld
name: Amplitude Identify Api Context
namespaces:
- prefix: amplitude
  uri: https://amplitude.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: $set
  type: reference
- container: ''
  name: $setOnce
  type: reference
- container: ''
  name: $add
  type: reference
- container: ''
  name: $append
  type: reference
- container: ''
  name: $prepend
  type: reference
- container: ''
  name: $unset
  type: reference
- container: ''
  name: $remove
  type: reference
- container: ''
  name: userId
  type: string
- container: ''
  name: deviceId
  type: string
- container: ''
  name: userProperties
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: serverUploadTime
  type: integer
- container: ''
  name: eventsIngested
  type: integer
- container: ''
  name: apiKey
  type: string
- container: set
  name: identification
  type: reference
property_count: 15
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-identify-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UserPropertyOperations\": \"amplitude:UserPropertyOperations\",\n    \"Identification\": \"amplitude:Identification\",\n    \"IdentifyResponse\": \"amplitude:IdentifyResponse\",\n    \"IdentifyRequestForm\": \"amplitude:IdentifyRequestForm\",\n    \"IdentifyRequestBody\": \"amplitude:IdentifyRequestBody\",\n    \"$set\": {\n      \"@id\": \"amplitude:$set\",\n      \"@type\": \"@id\"\n    },\n    \"$setOnce\": {\n      \"@id\": \"amplitude:$setOnce\",\n      \"@type\": \"@id\"\n    },\n    \"$add\": {\n      \"@id\": \"amplitude:$add\",\n      \"@type\": \"@id\"\n    },\n    \"$append\": {\n      \"@id\": \"amplitude:$append\",\n      \"@type\": \"@id\"\n    },\n    \"$prepend\": {\n      \"@id\": \"amplitude:$prepend\",\n    \
  \  \"@type\": \"@id\"\n    },\n    \"$unset\": {\n      \"@id\": \"amplitude:$unset\",\n      \"@type\": \"@id\"\n    },\n    \"$remove\": {\n      \"@id\": \"amplitude:$remove\",\n      \"@type\": \"@id\"\n    },\n    \"userId\": {\n      \"@id\": \"amplitude:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceId\": {\n      \"@id\": \"amplitude:device_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProperties\": {\n      \"@id\": \"amplitude:user_properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amplitude:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serverUploadTime\": {\n      \"@id\": \"amplitude:server_upload_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventsIngested\": {\n      \"@id\": \"amplitude:events_ingested\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"apiKey\": {\n      \"@id\": \"amplitude:api_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identification\": {\n      \"@id\"\
  : \"amplitude:identification\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-identify-api-context.jsonld
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---
