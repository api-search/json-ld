---
class_count: 9
classes:
- name
- description
- url
- version
- license
- SoftwareSourceCode
- SoftwareApplication
- programmingLanguage
- codeRepository
context_file: json-ld/redux-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redux/refs/heads/main/json-ld/redux-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redux from Redux.
layout: jsonld
name: Redux Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: redux
  uri: https://redux.js.org/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Store
  type: reference
- container: ''
  name: state
  type: ''
- container: ''
  name: Action
  type: reference
- container: ''
  name: actionType
  type: string
- container: ''
  name: payload
  type: ''
- container: ''
  name: Reducer
  type: reference
- container: ''
  name: Middleware
  type: reference
- container: ''
  name: Selector
  type: reference
- container: ''
  name: Slice
  type: reference
- container: ''
  name: dispatch
  type: ''
- container: ''
  name: subscribe
  type: ''
property_count: 11
provider_name: Redux
provider_slug: redux
slug: redux-context
source_filename: redux-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"redux\": \"https://redux.js.org/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:softwareVersion\",\n    \"license\": \"schema:license\",\n    \"Store\": {\n      \"@id\": \"redux:Store\",\n      \"@type\": \"@id\",\n      \"description\": \"The Redux store that holds the application state tree.\"\n    },\n    \"state\": {\n      \"@id\": \"redux:state\",\n      \"description\": \"The current immutable state tree of the Redux store.\"\n    },\n    \"Action\": {\n      \"@id\": \"redux:Action\",\n      \"@type\": \"@id\",\n      \"description\": \"A plain object that describes a state change in the Redux store.\"\n    },\n    \"actionType\": {\n      \"@id\": \"redux:actionType\",\n      \"@type\": \"xsd:string\",\n      \"description\"\
  : \"The type identifier for a Redux action.\"\n    },\n    \"payload\": {\n      \"@id\": \"redux:payload\",\n      \"description\": \"The data carried by a Redux action.\"\n    },\n    \"Reducer\": {\n      \"@id\": \"redux:Reducer\",\n      \"@type\": \"@id\",\n      \"description\": \"A pure function that specifies how the application state changes in response to actions.\"\n    },\n    \"Middleware\": {\n      \"@id\": \"redux:Middleware\",\n      \"@type\": \"@id\",\n      \"description\": \"An extension to the Redux dispatch mechanism providing a third-party extension point.\"\n    },\n    \"Selector\": {\n      \"@id\": \"redux:Selector\",\n      \"@type\": \"@id\",\n      \"description\": \"A function that computes derived data from the Redux state tree.\"\n    },\n    \"Slice\": {\n      \"@id\": \"redux:Slice\",\n      \"@type\": \"@id\",\n      \"description\": \"A Redux Toolkit abstraction combining initial state, reducers, and action creators for a feature domain.\"\n    },\n\
  \    \"dispatch\": {\n      \"@id\": \"redux:dispatch\",\n      \"description\": \"The Redux store method that triggers a state change by sending an action.\"\n    },\n    \"subscribe\": {\n      \"@id\": \"redux:subscribe\",\n      \"description\": \"The Redux store method for registering a listener on state changes.\"\n    },\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"codeRepository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redux/refs/heads/main/json-ld/redux-context.jsonld
tags:
- Flux Architecture
- Frontend
- Javascript
- Predictable State
- React
- State Management
- Typescript
- JSON-LD
- Linked Data
- Semantic Web
---
