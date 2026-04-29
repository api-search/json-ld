---
class_count: 1
classes:
- Instance
context_file: json-ld/amazon-lightsail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lightsail/refs/heads/main/json-ld/amazon-lightsail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lightsail from Amazon Lightsail.
layout: jsonld
name: Amazon Lightsail Context
namespaces:
- prefix: lightsail
  uri: https://lightsail.amazonaws.com/schema/
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
provider_name: Amazon Lightsail
provider_slug: amazon-lightsail
slug: amazon-lightsail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lightsail\": \"https://lightsail.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Instance\": \"lightsail:Instance\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lightsail:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lightsail:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n\
  \  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lightsail/refs/heads/main/json-ld/amazon-lightsail-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
