---
api_specs:
- filename: appmixer-api-openapi.yml
  format: yaml
  label: Appmixer API
  slug: appmixer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appmixer/refs/heads/main/openapi/appmixer-api-openapi.yml
class_count: 2
classes:
- name
- description
context_file: json-ld/appmixer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appmixer/refs/heads/main/json-ld/appmixer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appmixer from Appmixer.
layout: jsonld
name: Appmixer Context
namespaces:
- prefix: appmixer
  uri: https://api.appmixer.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: flowId
  type: string
- container: ''
  name: stage
  type: string
- container: ''
  name: btime
  type: dateTime
- container: ''
  name: mtime
  type: dateTime
- container: ''
  name: customFields
  type: '@json'
- container: ''
  name: accountId
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: profileInfo
  type: '@json'
- container: ''
  name: valid
  type: boolean
- container: ''
  name: fileId
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: storeId
  type: string
- container: ''
  name: componentId
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: plan
  type: string
- container: ''
  name: token
  type: string
property_count: 18
provider_name: Appmixer
provider_slug: appmixer
slug: appmixer-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"appmixer\": \"https://api.appmixer.com/\",\n    \"flowId\": {\n      \"@id\": \"appmixer:flowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stage\": {\n      \"@id\": \"appmixer:stage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"btime\": {\n      \"@id\": \"appmixer:btime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mtime\": {\n      \"@id\": \"appmixer:mtime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"customFields\": {\n      \"@id\": \"appmixer:customFields\",\n      \"@type\": \"@json\"\n    },\n    \"accountId\": {\n      \"@id\": \"appmixer:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"appmixer:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileInfo\": {\n      \"@id\": \"appmixer:profileInfo\",\n      \"@type\": \"@json\"\n    },\n    \"valid\": {\n      \"@id\": \"appmixer:valid\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"fileId\": {\n      \"@id\": \"appmixer:fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"appmixer:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"appmixer:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"appmixer:storeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentId\": {\n      \"@id\": \"appmixer:componentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"appmixer:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"appmixer:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plan\": {\n      \"@id\": \"appmixer:plan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"appmixer:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\
  ,\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appmixer/refs/heads/main/json-ld/appmixer-context.jsonld
tags:
- Agentic
- Automation
- Embedded iPaaS
- Integrations
- Low-Code
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
