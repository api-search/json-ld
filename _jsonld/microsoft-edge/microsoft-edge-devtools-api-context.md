---
api_specs:
- filename: microsoft-edge-addons-api.yaml
  format: yaml
  label: Microsoft Edge Add-ons API
  slug: edge-addons-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/openapi/microsoft-edge-addons-api.yaml
- filename: microsoft-edge-devtools-api.yaml
  format: yaml
  label: Microsoft Edge DevTools Protocol HTTP API
  slug: edge-devtools-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/openapi/microsoft-edge-devtools-api.yaml
class_count: 3
classes:
- Target
- BrowserVersion
- ProtocolSchema
context_file: json-ld/microsoft-edge-devtools-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/json-ld/microsoft-edge-devtools-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Edge Devtools Api from Microsoft Edge.
layout: jsonld
name: Microsoft Edge Devtools Api Context
namespaces:
- prefix: edge
  uri: https://developer.microsoft.com/microsoft-edge/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: devtoolsFrontendUrl
  type: string
- container: ''
  name: faviconUrl
  type: reference
- container: ''
  name: webSocketDebuggerUrl
  type: string
- container: ''
  name: browser
  type: string
- container: ''
  name: protocolVersion
  type: string
- container: ''
  name: userAgent
  type: string
- container: ''
  name: v8Version
  type: string
- container: ''
  name: webKitVersion
  type: string
- container: set
  name: domains
  type: ''
- container: set
  name: commands
  type: ''
- container: set
  name: events
  type: ''
property_count: 16
provider_name: Microsoft Edge
provider_slug: microsoft-edge
slug: microsoft-edge-devtools-api-context
source_filename: microsoft-edge-devtools-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"edge\": \"https://developer.microsoft.com/microsoft-edge/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Target\": \"edge:Target\",\n    \"BrowserVersion\": \"edge:BrowserVersion\",\n    \"ProtocolSchema\": \"edge:ProtocolSchema\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"edge:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"devtoolsFrontendUrl\": {\n      \"@id\": \"edge:devtools_frontend_url\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"faviconUrl\": {\n      \"@id\": \"edge:favicon_url\",\n      \"@type\": \"@id\"\n    },\n    \"webSocketDebuggerUrl\": {\n      \"@id\": \"edge:web_socket_debugger_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"browser\": {\n      \"@id\": \"edge:browser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocolVersion\": {\n      \"@id\": \"edge:protocol_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAgent\": {\n      \"@id\": \"edge:user_agent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"v8Version\": {\n      \"@id\": \"edge:v8_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webKitVersion\": {\n      \"@id\": \"edge:webkit_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"edge:domains\",\n      \"@container\": \"@set\"\n    },\n    \"commands\": {\n      \"@id\": \"edge:commands\",\n      \"@container\": \"@set\"\n    },\n    \"events\": {\n      \"@id\": \"edge:events\",\n      \"@container\": \"\
  @set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/json-ld/microsoft-edge-devtools-api-context.jsonld
tags:
- Browser
- Chromium
- Developer Tools
- Edge
- Extensions
- Microsoft
- Progressive Web Apps
- Web Development
- WebView
- JSON-LD
- Linked Data
- Semantic Web
---
