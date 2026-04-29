---
api_specs:
- filename: amazon-api-gateway-openapi.yaml
  format: yaml
  label: Amazon API Gateway REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/openapi/amazon-api-gateway-openapi.yaml
- filename: amazon-api-gateway-websocket-asyncapi.yml
  format: yaml
  label: Amazon API Gateway WebSocket API
  slug: websocket-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/asyncapi/amazon-api-gateway-websocket-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-api-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/json-ld/amazon-api-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Api Gateway from Amazon API Gateway.
layout: jsonld
name: Amazon Api Gateway Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: version
  type: string
- container: ''
  name: warnings
  type: ''
- container: ''
  name: binaryMediaTypes
  type: ''
- container: ''
  name: minimumCompressionSize
  type: integer
- container: ''
  name: apiKeySource
  type: string
- container: ''
  name: endpointConfiguration
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: tags
  type: ''
- container: ''
  name: disableExecuteApiEndpoint
  type: boolean
property_count: 13
provider_name: Amazon API Gateway
provider_slug: amazon-api-gateway
slug: amazon-api-gateway-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"createdDate\": {\n      \"@id\": \"schema:createdDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warnings\": {\n      \"@id\": \"schema:warnings\"\n    },\n    \"binaryMediaTypes\": {\n      \"@id\": \"schema:binaryMediaTypes\"\n    },\n    \"minimumCompressionSize\": {\n      \"@id\": \"schema:minimumCompressionSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"apiKeySource\": {\n      \"@id\": \"schema:apiKeySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointConfiguration\": {\n      \"@id\": \"schema:endpointConfiguration\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"schema:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:tags\"\n    },\n    \"disableExecuteApiEndpoint\": {\n      \"@id\": \"schema:disableExecuteApiEndpoint\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/json-ld/amazon-api-gateway-context.jsonld
tags:
- AWS
- Gateway
- HTTP API
- REST API
- Serverless
- WebSocket
- JSON-LD
- Linked Data
- Semantic Web
---
