---
api_specs:
- filename: appium-server-openapi.yaml
  format: yaml
  label: Appium Server API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appium/refs/heads/main/openapi/appium-server-openapi.yaml
class_count: 7
classes:
- FindElementRequest
- ErrorResponse
- ActionSequence
- SessionInfo
- AppIdRequest
- Cookie
- name
context_file: json-ld/appium-server-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appium/refs/heads/main/json-ld/appium-server-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appium Server from Appium.
layout: jsonld
name: Appium Server Context
namespaces:
- prefix: appium
  uri: https://appium.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: using
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: parameters
  type: reference
- container: set
  name: actions
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: appId
  type: string
- container: ''
  name: bundleId
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: domain
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: httpOnly
  type: boolean
- container: ''
  name: secure
  type: boolean
- container: ''
  name: expiry
  type: integer
property_count: 15
provider_name: Appium
provider_slug: appium
slug: appium-server-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"appium\": \"https://appium.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FindElementRequest\": \"appium:FindElementRequest\",\n    \"using\": {\n      \"@id\": \"appium:using\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"appium:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": \"appium:ErrorResponse\",\n    \"ActionSequence\": \"appium:ActionSequence\",\n    \"type\": {\n      \"@id\": \"appium:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"appium:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"appium:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"actions\": {\n      \"@id\": \"appium:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"SessionInfo\": \"appium:SessionInfo\",\n    \"capabilities\": {\n      \"@id\": \"appium:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"AppIdRequest\": \"appium:AppIdRequest\",\n    \"appId\": {\n      \"@id\": \"appium:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundleId\": {\n      \"@id\": \"appium:bundleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"appium:options\",\n      \"@type\": \"@id\"\n    },\n    \"Cookie\": \"appium:Cookie\",\n    \"name\": \"schema:name\",\n    \"domain\": {\n      \"@id\": \"appium:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"appium:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpOnly\": {\n      \"@id\": \"appium:httpOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"secure\": {\n      \"@id\": \"appium:secure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"expiry\": {\n      \"@id\": \"appium:expiry\",\n      \"@type\": \"\
  xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appium/refs/heads/main/json-ld/appium-server-context.jsonld
tags:
- Android
- Cross-Platform
- iOS
- Mobile Testing
- Open Source
- OpenJS Foundation
- Test Automation
- WebDriver
- JSON-LD
- Linked Data
- Semantic Web
---
