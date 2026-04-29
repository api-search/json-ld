---
class_count: 3
classes:
- UsagePlan
- UsagePlans
- name
context_file: json-ld/aws-api-gateway-v1-usage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-usage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V1 Usage from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V1 Usage Context
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
- container: set
  name: items
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: throttle
  type: reference
- container: ''
  name: burstLimit
  type: integer
- container: ''
  name: rateLimit
  type: decimal
- container: ''
  name: quota
  type: reference
- container: ''
  name: limit
  type: integer
- container: ''
  name: period
  type: string
property_count: 8
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v1-usage-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UsagePlan\": \"aws:UsagePlan\",\n    \"UsagePlans\": \"aws:UsagePlans\",\n    \"items\": {\n      \"@id\": \"aws:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"throttle\": {\n      \"@id\": \"aws:throttle\",\n      \"@type\": \"@id\"\n    },\n    \"burstLimit\": {\n      \"@id\": \"aws:burstLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rateLimit\": {\n      \"@id\": \"aws:rateLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"quota\": {\n      \"@id\": \"aws:quota\",\n      \"@type\": \"@id\"\n    },\n    \"limit\": {\n      \"@id\": \"aws:limit\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"period\": {\n      \"@id\": \"aws:period\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-usage-context.jsonld
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
