---
class_count: 1
classes:
- Message
context_file: json-ld/amazon-q-openapi-message-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-message-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Q Openapi Message from Amazon Q.
layout: jsonld
name: Amazon Q Openapi Message Context
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
  name: messageId
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: time
  type: dateTime
property_count: 4
provider_name: Amazon Q
provider_slug: amazon-q
slug: amazon-q-openapi-message-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Message\": \"aws:Message\",\n    \"messageId\": {\n      \"@id\": \"aws:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"aws:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"aws:time\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-message-context.jsonld
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
