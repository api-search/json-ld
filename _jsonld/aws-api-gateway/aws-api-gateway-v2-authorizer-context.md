---
class_count: 1
classes:
- Authorizer
context_file: json-ld/aws-api-gateway-v2-authorizer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-authorizer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V2 Authorizer from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V2 Authorizer Context
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
  name: AuthorizerId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: AuthorizerType
  type: string
- container: set
  name: IdentitySource
  type: string
property_count: 4
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v2-authorizer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Authorizer\": \"aws:Authorizer\",\n    \"AuthorizerId\": {\n      \"@id\": \"aws:AuthorizerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizerType\": {\n      \"@id\": \"aws:AuthorizerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentitySource\": {\n      \"@id\": \"aws:IdentitySource\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-authorizer-context.jsonld
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
