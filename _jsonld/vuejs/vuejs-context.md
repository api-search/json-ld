---
class_count: 3
classes:
- SoftwareApplication
- SoftwareLibrary
- SoftwareSourceCode
context_file: json-ld/vuejs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vuejs/refs/heads/main/json-ld/vuejs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vuejs from Vue.js.
layout: jsonld
name: Vuejs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vue
  uri: https://vuejs.org/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Vue
  type: schema:SoftwareApplication
- container: ''
  name: Component
  type: schema:SoftwareSourceCode
- container: ''
  name: props
  type: reference
- container: ''
  name: emits
  type: reference
- container: ''
  name: computed
  type: reference
- container: ''
  name: Composable
  type: schema:SoftwareSourceCode
- container: ''
  name: Store
  type: schema:SoftwareApplication
- container: ''
  name: Route
  type: schema:WebPage
- container: ''
  name: Router
  type: schema:SoftwareApplication
- container: ''
  name: Directive
  type: schema:SoftwareSourceCode
- container: ''
  name: Plugin
  type: schema:SoftwareApplication
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: programmingLanguage
  type: string
- container: ''
  name: license
  type: reference
- container: ''
  name: codeRepository
  type: reference
property_count: 17
provider_name: Vue.js
provider_slug: vuejs
slug: vuejs-context
source_filename: vuejs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vue\": \"https://vuejs.org/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareLibrary\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n\n    \"Vue\": {\n      \"@id\": \"vue:Vue\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n\n    \"Component\": {\n      \"@id\": \"vue:Component\",\n      \"@type\": \"schema:SoftwareSourceCode\"\n    },\n\n    \"props\": {\n      \"@id\": \"vue:props\",\n      \"@type\": \"@id\"\n    },\n\n    \"emits\": {\n      \"@id\": \"vue:emits\",\n      \"@type\": \"@id\"\n    },\n\n    \"computed\": {\n      \"@id\": \"vue:computed\",\n      \"@type\": \"@id\"\n    },\n\n    \"Composable\": {\n      \"@id\": \"vue:Composable\",\n      \"@type\": \"schema:SoftwareSourceCode\"\n    },\n\n    \"Store\": {\n   \
  \   \"@id\": \"vue:Store\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n\n    \"Route\": {\n      \"@id\": \"vue:Route\",\n      \"@type\": \"schema:WebPage\"\n    },\n\n    \"Router\": {\n      \"@id\": \"vue:Router\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n\n    \"Directive\": {\n      \"@id\": \"vue:Directive\",\n      \"@type\": \"schema:SoftwareSourceCode\"\n    },\n\n    \"Plugin\": {\n      \"@id\": \"vue:Plugin\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"programmingLanguage\": {\n      \"@id\": \"schema:programmingLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"license\": {\n      \"@id\": \"schema:license\"\
  ,\n      \"@type\": \"@id\"\n    },\n\n    \"codeRepository\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vuejs/refs/heads/main/json-ld/vuejs-context.jsonld
tags:
- Component-Based
- Framework
- Frontend
- JavaScript
- Open Source
- UI
- JSON-LD
- Linked Data
- Semantic Web
---
