---
api_specs:
- filename: xiaomi-open-api-openapi.yml
  format: yaml
  label: Xiaomi Open API
  slug: xiaomi-open-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-open-api-openapi.yml
- filename: xiaomi-galaxy-fds-openapi.yml
  format: yaml
  label: Xiaomi Galaxy FDS API
  slug: xiaomi-galaxy-fds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-galaxy-fds-openapi.yml
- filename: xiaomi-mimo-api-openapi.yml
  format: yaml
  label: Xiaomi MiMo AI API
  slug: xiaomi-mimo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/openapi/xiaomi-mimo-api-openapi.yml
class_count: 20
classes:
- UserProfile
- nickname
- miliaoId
- avatarUrl
- email
- phone
- openId
- Bucket
- bucketName
- Object
- objectName
- ChatCompletion
- model
- messages
- role
- content
- usage
- promptTokens
- completionTokens
- totalTokens
context_file: json-ld/xiaomi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-ld/xiaomi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Xiaomi from Xiaomi.
layout: jsonld
name: Xiaomi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xiaomi
  uri: https://dev.mi.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 2
provider_name: Xiaomi
provider_slug: xiaomi
slug: xiaomi-context
source_filename: xiaomi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xiaomi\": \"https://dev.mi.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"UserProfile\": \"schema:Person\",\n    \"nickname\": \"schema:name\",\n    \"miliaoId\": \"xiaomi:miliaoId\",\n    \"avatarUrl\": \"schema:image\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"openId\": \"xiaomi:openId\",\n\n    \"Bucket\": \"xiaomi:Bucket\",\n    \"bucketName\": \"xiaomi:bucketName\",\n    \"Object\": \"schema:DigitalDocument\",\n    \"objectName\": \"schema:name\",\n\n    \"ChatCompletion\": \"xiaomi:ChatCompletion\",\n    \"model\": \"xiaomi:model\",\n    \"messages\": \"xiaomi:messages\",\n    \"role\": \"xiaomi:role\",\n    \"content\": \"schema:text\",\n    \"usage\": \"xiaomi:usage\",\n    \"promptTokens\": \"xiaomi:promptTokens\",\n    \"completionTokens\": \"xiaomi:completionTokens\",\n    \"totalTokens\": \"xiaomi:totalTokens\"\
  ,\n\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/xiaomi/refs/heads/main/json-ld/xiaomi-context.jsonld
tags:
- Consumer Electronics
- IoT
- Smart Home
- Mobile
- Artificial Intelligence
- Cloud Storage
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
