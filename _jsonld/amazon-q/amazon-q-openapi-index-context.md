---
class_count: 1
classes:
- Index
context_file: json-ld/amazon-q-openapi-index-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-index-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Q Openapi Index from Amazon Q.
layout: jsonld
name: Amazon Q Openapi Index Context
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
  name: indexId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: status
  type: string
property_count: 3
provider_name: Amazon Q
provider_slug: amazon-q
slug: amazon-q-openapi-index-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Index\": \"aws:Index\",\n    \"indexId\": {\n      \"@id\": \"aws:indexId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"aws:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-index-context.jsonld
tags:
- Artificial Intelligence
- Assistant
- AWS
- Enterprise
- Generative AI
- JSON-LD
- Linked Data
- Semantic Web
---
