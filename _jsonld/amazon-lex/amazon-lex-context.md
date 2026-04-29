---
class_count: 2
classes:
- Bot
- Intent
context_file: json-ld/amazon-lex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lex/refs/heads/main/json-ld/amazon-lex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lex from Amazon Lex.
layout: jsonld
name: Amazon Lex Context
namespaces:
- prefix: lex
  uri: https://lex.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 7
provider_name: Amazon Lex
provider_slug: amazon-lex
slug: amazon-lex-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lex\": \"https://lex.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Bot\": \"lex:Bot\",\n    \"Intent\": \"lex:Intent\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lex:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lex:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lex/refs/heads/main/json-ld/amazon-lex-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
