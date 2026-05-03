---
class_count: 0
classes: []
context_file: json-ld/twirp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/twirp/refs/heads/main/json-ld/twirp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Twirp from Twirp.
layout: jsonld
name: Twirp Context
namespaces:
- prefix: twirp
  uri: https://twitchtv.github.io/twirp/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: Method
  type: ''
- container: ''
  name: TwirpURL
  type: ''
- container: ''
  name: TwirpError
  type: ''
- container: ''
  name: ProtoMessage
  type: ''
property_count: 5
provider_name: Twirp
provider_slug: twirp
slug: twirp-context
source_filename: twirp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"twirp\": \"https://twitchtv.github.io/twirp/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n\n    \"Service\": {\n      \"@id\": \"twirp:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"package\": \"twirp:protoPackage\",\n        \"methods\": \"twirp:rpcMethods\"\n      }\n    },\n\n    \"Method\": {\n      \"@id\": \"twirp:Method\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"inputType\": \"twirp:inputMessage\",\n        \"outputType\": \"twirp:outputMessage\",\n        \"httpMethod\": \"schema:httpMethod\"\n      }\n    },\n\n    \"TwirpURL\": {\n      \"@id\": \"twirp:TwirpURL\",\n      \"@context\": {\n        \"baseUri\": {\n          \"@id\": \"schema:url\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"prefix\": \"twirp:urlPrefix\",\n        \"package\": \"twirp:protoPackage\",\n        \"service\": \"twirp:serviceName\",\n        \"method\": \"twirp:methodName\"\n      }\n    },\n\n    \"TwirpError\": {\n      \"@id\": \"twirp:Error\",\n      \"@context\": {\n        \"code\": \"twirp:errorCode\",\n        \"msg\": \"schema:description\",\n        \"meta\": \"twirp:errorMeta\"\n      }\n    },\n\n    \"ProtoMessage\": {\n      \"@id\": \"twirp:ProtoMessage\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"fields\": \"twirp:messageFields\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/twirp/refs/heads/main/json-ld/twirp-context.jsonld
tags:
- Protocol Buffers
- RPC
- Go
- SDKs
- Open Source
- Protobuf
- JSON-LD
- Linked Data
- Semantic Web
---
