---
class_count: 5
classes:
- Incident
- IncidentCollection
- date
- description
- name
context_file: json-ld/2020-police-brutality-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/json-ld/2020-police-brutality-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 2020 Police Brutality from 2020 Police Brutality.
layout: jsonld
name: 2020 Police Brutality Context
namespaces:
- prefix: pb2020
  uri: https://2020pb.github.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: city
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: dateText
  type: string
- container: ''
  name: editAt
  type: reference
- container: ''
  name: geolocation
  type: string
- container: ''
  name: help
  type: reference
- container: ''
  name: id
  type: string
- container: set
  name: links
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: updatedAt
  type: dateTime
property_count: 11
provider_name: 2020 Police Brutality
provider_slug: 2020-police-brutality
slug: 2020-police-brutality-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pb2020\": \"https://2020pb.github.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Incident\": \"pb2020:Incident\",\n    \"IncidentCollection\": \"pb2020:IncidentCollection\",\n    \"city\": {\n      \"@id\": \"pb2020:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pb2020:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": \"schema:dateCreated\",\n    \"dateText\": {\n      \"@id\": \"pb2020:date_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"editAt\": {\n      \"@id\": \"pb2020:edit_at\",\n      \"@type\": \"@id\"\n    },\n    \"geolocation\": {\n      \"@id\": \"pb2020:geolocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"help\": {\n      \"@id\": \"pb2020:help\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n\
  \      \"@id\": \"pb2020:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"links\": {\n      \"@id\": \"pb2020:links\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"state\": {\n      \"@id\": \"pb2020:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pb2020:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"pb2020:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/json-ld/2020-police-brutality-context.jsonld
tags:
- Brutality
- Civil Rights
- Policing
- Public Data
- JSON-LD
- Linked Data
- Semantic Web
---
