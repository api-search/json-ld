---
class_count: 0
classes: []
context_file: json-ld/amazon-amplify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/json-ld/amazon-amplify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Amplify from Amazon Amplify.
layout: jsonld
name: Amazon Amplify Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: appId
  type: string
- container: ''
  name: appArn
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: repository
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: defaultDomain
  type: string
- container: ''
  name: productionBranch
  type: string
property_count: 10
provider_name: Amazon Amplify
provider_slug: amazon-amplify
slug: amazon-amplify-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"appId\": {\n      \"@id\": \"schema:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appArn\": {\n      \"@id\": \"schema:appArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"repository\": {\n      \"@id\": \"schema:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"schema:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"schema:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"schema:updateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"defaultDomain\": {\n      \"@id\": \"schema:defaultDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productionBranch\"\
  : {\n      \"@id\": \"schema:productionBranch\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/json-ld/amazon-amplify-context.jsonld
tags:
- AWS
- Frontend
- Full Stack
- Hosting
- Mobile Development
- Web Applications
- JSON-LD
- Linked Data
- Semantic Web
---
