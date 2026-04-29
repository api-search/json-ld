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
- Product
- Submission
- PackageUploadResult
context_file: json-ld/microsoft-edge-addons-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/json-ld/microsoft-edge-addons-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Edge Addons Api from Microsoft Edge.
layout: jsonld
name: Microsoft Edge Addons Api Context
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
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: lastUpdatedUtc
  type: dateTime
- container: ''
  name: category
  type: string
- container: ''
  name: productId
  type: string
- container: ''
  name: createdUtc
  type: dateTime
- container: ''
  name: completedUtc
  type: dateTime
- container: ''
  name: operationId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: notes
  type: string
property_count: 13
provider_name: Microsoft Edge
provider_slug: microsoft-edge
slug: microsoft-edge-addons-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"edge\": \"https://developer.microsoft.com/microsoft-edge/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"edge:Product\",\n    \"Submission\": \"edge:Submission\",\n    \"PackageUploadResult\": \"edge:PackageUploadResult\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"edge:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedUtc\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"category\": {\n      \"@id\": \"edge:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"edge:product_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdUtc\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedUtc\": {\n      \"@id\": \"edge:completed_utc\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"operationId\": {\n      \"@id\": \"edge:operation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"edge:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notes\": {\n      \"@id\": \"edge:notes\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-edge/refs/heads/main/json-ld/microsoft-edge-addons-api-context.jsonld
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
