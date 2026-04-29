---
class_count: 1
classes:
- Route
context_file: json-ld/aws-api-gateway-v2-route-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-route-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V2 Route from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V2 Route Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: RouteId
  type: string
- container: ''
  name: RouteKey
  type: string
- container: ''
  name: Target
  type: string
- container: ''
  name: AuthorizationType
  type: string
property_count: 4
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v2-route-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Route\": \"aws:Route\",\n    \"RouteId\": {\n      \"@id\": \"aws:RouteId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RouteKey\": {\n      \"@id\": \"aws:RouteKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Target\": {\n      \"@id\": \"aws:Target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizationType\": {\n      \"@id\": \"aws:AuthorizationType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-route-context.jsonld
tags:
- API Gateway
- AWS
- Cloud
- REST
- WebSocket
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
