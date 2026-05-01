---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Assistant API
  slug: google-assistant
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-assistant/refs/heads/main/openapi/openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-assistant.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-assistant/refs/heads/main/json-ld/google-assistant.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Assistant from Google Assistant.
layout: jsonld
name: Google Assistant Context
namespaces:
- prefix: gassist
  uri: https://developers.google.com/assistant/sdk/reference/rpc#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: DeviceModel
  type: ''
- container: ''
  name: DeviceInstance
  type: ''
- container: ''
  name: deviceModelId
  type: string
- container: ''
  name: deviceType
  type: string
- container: list
  name: traits
  type: ''
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: textInput
  type: string
- container: ''
  name: conversationState
  type: string
property_count: 9
provider_name: Google Assistant
provider_slug: google-assistant
slug: google-assistant
source_filename: google-assistant.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gassist\": \"https://developers.google.com/assistant/sdk/reference/rpc#\",\n    \"DeviceModel\": {\n      \"@id\": \"gassist:DeviceModel\"\n    },\n    \"DeviceInstance\": {\n      \"@id\": \"gassist:DeviceInstance\"\n    },\n    \"deviceModelId\": {\n      \"@id\": \"gassist:deviceModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceType\": {\n      \"@id\": \"gassist:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"traits\": {\n      \"@id\": \"gassist:traits\",\n      \"@container\": \"@list\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"https://schema.org/manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"https://schema.org/name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"textInput\": {\n      \"@id\": \"gassist:textInput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversationState\": {\n      \"@id\": \"gassist:conversationState\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-assistant/refs/heads/main/json-ld/google-assistant.jsonld
tags:
- Actions on Google
- Conversational AI
- Google Assistant
- Natural Language
- Smart Home
- Voice Assistant
- JSON-LD
- Linked Data
- Semantic Web
---
