---
api_specs:
- filename: academy-software-foundation-opencue.yaml
  format: yaml
  label: OpenCue
  slug: opencue
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/openapi/academy-software-foundation-opencue.yaml
class_count: 5
classes:
- Host
- name
- Job
- Layer
- Show
context_file: json-ld/academy-software-foundation-opencue-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/json-ld/academy-software-foundation-opencue-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Academy Software Foundation Opencue from Academy Software Foundation.
layout: jsonld
name: Academy Software Foundation Opencue Context
namespaces:
- prefix: aswf
  uri: https://aswf.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: lock
  type: string
- container: ''
  name: totalCores
  type: integer
- container: ''
  name: idleCores
  type: integer
- container: ''
  name: totalMemory
  type: integer
- container: ''
  name: idleMemory
  type: integer
- container: ''
  name: load
  type: integer
- container: ''
  name: show
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: totalFrames
  type: integer
- container: ''
  name: doneFrames
  type: integer
- container: ''
  name: runningFrames
  type: integer
- container: ''
  name: deadFrames
  type: integer
- container: ''
  name: waitingFrames
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: minCores
  type: integer
- container: ''
  name: maxCores
  type: integer
- container: ''
  name: threadable
  type: boolean
- container: ''
  name: active
  type: boolean
- container: ''
  name: defaultMinCores
  type: integer
- container: ''
  name: defaultMaxCores
  type: integer
property_count: 22
provider_name: Academy Software Foundation
provider_slug: academy-software-foundation
slug: academy-software-foundation-opencue-context
source_filename: academy-software-foundation-opencue-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aswf\": \"https://aswf.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Host\": \"aswf:Host\",\n    \"id\": {\n      \"@id\": \"aswf:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"state\": {\n      \"@id\": \"aswf:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lock\": {\n      \"@id\": \"aswf:lock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCores\": {\n      \"@id\": \"aswf:totalCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"idleCores\": {\n      \"@id\": \"aswf:idleCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalMemory\": {\n      \"@id\": \"aswf:totalMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"idleMemory\": {\n      \"@id\": \"aswf:idleMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"load\": {\n      \"@id\": \"aswf:load\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"Job\": \"aswf:Job\",\n    \"show\": {\n      \"@id\": \"aswf:show\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aswf:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalFrames\": {\n      \"@id\": \"aswf:totalFrames\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"doneFrames\": {\n      \"@id\": \"aswf:doneFrames\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runningFrames\": {\n      \"@id\": \"aswf:runningFrames\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deadFrames\": {\n      \"@id\": \"aswf:deadFrames\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"waitingFrames\": {\n      \"@id\": \"aswf:waitingFrames\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Layer\": \"aswf:Layer\",\n    \"type\": {\n      \"@id\": \"aswf:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minCores\": {\n      \"@id\": \"aswf:minCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxCores\": {\n\
  \      \"@id\": \"aswf:maxCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"threadable\": {\n      \"@id\": \"aswf:threadable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Show\": \"aswf:Show\",\n    \"active\": {\n      \"@id\": \"aswf:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"defaultMinCores\": {\n      \"@id\": \"aswf:defaultMinCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultMaxCores\": {\n      \"@id\": \"aswf:defaultMaxCores\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/academy-software-foundation/refs/heads/main/json-ld/academy-software-foundation-opencue-context.jsonld
tags:
- Animation
- Color Management
- Film
- Linux Foundation
- Open Source
- Rendering
- Standards
- Visual Effects
- VFX
- JSON-LD
- Linked Data
- Semantic Web
---
