---
class_count: 5
classes:
- id
- name
- description
- status
- created_at
context_file: json-ld/biogen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/json-ld/biogen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Biogen from Biogen.
layout: jsonld
name: Biogen Context
namespaces:
- prefix: bg
  uri: https://developer.biogen.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: services
  type: string
- container: ''
  name: requests_today
  type: integer
- container: ''
  name: requests_month
  type: integer
- container: ''
  name: key
  type: string
- container: ''
  name: keys
  type: string
property_count: 5
provider_name: Biogen
provider_slug: biogen
slug: biogen-context
source_filename: biogen-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bg\": \"https://developer.biogen.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"services\": {\n      \"@id\": \"bg:services\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requests_today\": {\n      \"@id\": \"bg:requests_today\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requests_month\": {\n      \"@id\": \"bg:requests_month\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"key\": {\n      \"@id\": \"bg:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": \"schema:dateCreated\",\n    \"keys\": {\n      \"@id\": \"bg:keys\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/biogen/refs/heads/main/json-ld/biogen-context.jsonld
tags:
- Biotechnology
- Healthcare
- Life Sciences
- Pharmaceuticals
- Neurology
- JSON-LD
- Linked Data
- Semantic Web
---
