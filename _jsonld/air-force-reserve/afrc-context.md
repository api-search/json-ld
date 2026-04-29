---
class_count: 3
classes:
- ReserveMember
- ReserveUnit
- CareerOpportunity
context_file: json-ld/afrc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/air-force-reserve/refs/heads/main/json-ld/afrc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Afrc from Air Force Reserve.
layout: jsonld
name: Afrc Context
namespaces:
- prefix: afrc
  uri: https://www.afrc.af.mil/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: serviceNumber
  type: string
- container: ''
  name: rank
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: afsc
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: mission
  type: string
- container: ''
  name: enlistmentDate
  type: date
property_count: 9
provider_name: Air Force Reserve
provider_slug: air-force-reserve
slug: afrc-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"afrc\": \"https://www.afrc.af.mil/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReserveMember\": \"afrc:ReserveMember\",\n    \"ReserveUnit\": \"afrc:ReserveUnit\",\n    \"CareerOpportunity\": \"afrc:CareerOpportunity\",\n    \"serviceNumber\": {\n      \"@id\": \"afrc:service_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rank\": {\n      \"@id\": \"afrc:rank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"afrc:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"afsc\": {\n      \"@id\": \"afrc:afsc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"mission\": {\n      \"@id\": \"afrc:mission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enlistmentDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/air-force-reserve/refs/heads/main/json-ld/afrc-context.jsonld
tags:
- Federal Government
- Military
- Defense
- Air Force
- United States Government
- JSON-LD
- Linked Data
- Semantic Web
---
