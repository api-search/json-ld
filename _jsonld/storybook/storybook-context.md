---
class_count: 6
classes:
- SoftwareApplication
- name
- description
- title
- framework
- version
context_file: json-ld/storybook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/storybook/refs/heads/main/json-ld/storybook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Storybook from Storybook.
layout: jsonld
name: Storybook Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
- prefix: Story
  uri: https://storybook.js.org/schema/Story
- prefix: ComponentMeta
  uri: https://storybook.js.org/schema/ComponentMeta
- prefix: ArgType
  uri: https://storybook.js.org/schema/ArgType
- prefix: Addon
  uri: https://storybook.js.org/schema/Addon
- prefix: args
  uri: https://storybook.js.org/schema/args
- prefix: argTypes
  uri: https://storybook.js.org/schema/argTypes
- prefix: parameters
  uri: https://storybook.js.org/schema/parameters
- prefix: decorators
  uri: https://storybook.js.org/schema/decorators
- prefix: play
  uri: https://storybook.js.org/schema/playFunction
- prefix: loaders
  uri: https://storybook.js.org/schema/loaders
- prefix: control
  uri: https://storybook.js.org/schema/control
- prefix: options
  uri: https://storybook.js.org/schema/options
properties:
- container: ''
  name: UIComponent
  type: reference
- container: ''
  name: component
  type: reference
- container: list
  name: tags
  type: ''
- container: ''
  name: required
  type: boolean
- container: ''
  name: license
  type: reference
- container: ''
  name: repository
  type: reference
- container: ''
  name: npmPackage
  type: reference
property_count: 7
provider_name: Storybook
provider_slug: storybook
slug: storybook-context
source_filename: storybook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://storybook.js.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"UIComponent\": {\n      \"@id\": \"https://storybook.js.org/schema/UIComponent\",\n      \"@type\": \"@id\"\n    },\n    \"Story\": \"https://storybook.js.org/schema/Story\",\n    \"ComponentMeta\": \"https://storybook.js.org/schema/ComponentMeta\",\n    \"ArgType\": \"https://storybook.js.org/schema/ArgType\",\n    \"Addon\": \"https://storybook.js.org/schema/Addon\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"title\": \"schema:name\",\n    \"component\": {\n      \"@id\": \"https://storybook.js.org/schema/component\",\n      \"@type\": \"@id\"\n    },\n    \"args\": \"https://storybook.js.org/schema/args\",\n    \"argTypes\": \"https://storybook.js.org/schema/argTypes\"\
  ,\n    \"parameters\": \"https://storybook.js.org/schema/parameters\",\n    \"decorators\": \"https://storybook.js.org/schema/decorators\",\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"play\": \"https://storybook.js.org/schema/playFunction\",\n    \"loaders\": \"https://storybook.js.org/schema/loaders\",\n    \"control\": \"https://storybook.js.org/schema/control\",\n    \"options\": \"https://storybook.js.org/schema/options\",\n    \"required\": {\n      \"@id\": \"schema:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"framework\": \"schema:runtimePlatform\",\n    \"version\": \"schema:softwareVersion\",\n    \"license\": {\n      \"@id\": \"doap:license\",\n      \"@type\": \"@id\"\n    },\n    \"repository\": {\n      \"@id\": \"doap:repository\",\n      \"@type\": \"@id\"\n    },\n    \"npmPackage\": {\n      \"@id\": \"https://storybook.js.org/schema/npmPackage\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/storybook/refs/heads/main/json-ld/storybook-context.jsonld
tags:
- Accessibility Testing
- Component Documentation
- Component Testing
- Design Systems
- Frontend Development
- Open Source
- React
- UI Components
- Visual Testing
- JSON-LD
- Linked Data
- Semantic Web
---
