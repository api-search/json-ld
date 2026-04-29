---
class_count: 1
classes:
- Conversation
context_file: json-ld/amazon-q-openapi-conversation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-conversation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Q Openapi Conversation from Amazon Q.
layout: jsonld
name: Amazon Q Openapi Conversation Context
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
  name: conversationId
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: createdAt
  type: dateTime
property_count: 3
provider_name: Amazon Q
provider_slug: amazon-q
slug: amazon-q-openapi-conversation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Conversation\": \"aws:Conversation\",\n    \"conversationId\": {\n      \"@id\": \"aws:conversationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"aws:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-conversation-context.jsonld
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
