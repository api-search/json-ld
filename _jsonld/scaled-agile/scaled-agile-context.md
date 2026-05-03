---
class_count: 1
classes:
- id
context_file: json-ld/scaled-agile-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scaled-agile/refs/heads/main/json-ld/scaled-agile-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scaled Agile from Scaled Agile.
layout: jsonld
name: Scaled Agile Context
namespaces:
- prefix: safe
  uri: https://scaledagileframework.com/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: SAFePI
  type: schema:Event
- container: ''
  name: SAFeART
  type: schema:Organization
- container: ''
  name: SAFeEpic
  type: schema:Project
- container: ''
  name: SAFeFeature
  type: schema:CreativeWork
- container: ''
  name: SAFeStory
  type: schema:CreativeWork
- container: ''
  name: SAFeTeam
  type: schema:Organization
- container: ''
  name: SAFeObjective
  type: schema:Goal
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: start_date
  type: date
- container: ''
  name: end_date
  type: date
- container: ''
  name: status
  type: string
- container: ''
  name: art
  type: reference
- container: list
  name: iterations
  type: ''
- container: list
  name: objectives
  type: ''
- container: list
  name: features
  type: ''
- container: ''
  name: business_value
  type: integer
- container: ''
  name: committed
  type: boolean
- container: ''
  name: team
  type: reference
- container: ''
  name: title
  type: string
property_count: 20
provider_name: Scaled Agile
provider_slug: scaled-agile
slug: scaled-agile-context
source_filename: scaled-agile-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"safe\": \"https://scaledagileframework.com/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SAFePI\": {\n      \"@id\": \"safe:ProgramIncrement\",\n      \"@type\": \"schema:Event\"\n    },\n    \"SAFeART\": {\n      \"@id\": \"safe:AgileReleaseTrain\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"SAFeEpic\": {\n      \"@id\": \"safe:Epic\",\n      \"@type\": \"schema:Project\"\n    },\n    \"SAFeFeature\": {\n      \"@id\": \"safe:Feature\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"SAFeStory\": {\n      \"@id\": \"safe:Story\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"SAFeTeam\": {\n      \"@id\": \"safe:AgileTeam\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"SAFeObjective\": {\n      \"@id\": \"safe:PIObjective\",\n      \"@type\": \"schema:Goal\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": {\n\
  \      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start_date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end_date\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"art\": {\n      \"@id\": \"safe:art\",\n      \"@type\": \"@id\"\n    },\n    \"iterations\": {\n      \"@id\": \"safe:iterations\",\n      \"@container\": \"@list\"\n    },\n    \"objectives\": {\n      \"@id\": \"safe:objectives\",\n      \"@container\": \"@list\"\n    },\n    \"features\": {\n      \"@id\": \"safe:features\",\n      \"@container\": \"@list\"\n    },\n    \"business_value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"committed\": {\n      \"@id\": \"safe:committed\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"team\": {\n      \"@id\": \"safe:team\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scaled-agile/refs/heads/main/json-ld/scaled-agile-context.jsonld
tags:
- Agile
- Business Agility
- DevOps
- Enterprise
- Lean
- Project Management
- SAFe
- Scaled Agile
- JSON-LD
- Linked Data
- Semantic Web
---
