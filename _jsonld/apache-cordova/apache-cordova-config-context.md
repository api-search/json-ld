---
class_count: 5
classes:
- Widget
- description
- email
- name
- version
context_file: json-ld/apache-cordova-config-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-config-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Cordova Config from Apache Cordova.
layout: jsonld
name: Apache Cordova Config Context
namespaces:
- prefix: cordova
  uri: https://cordova.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: androidVersioncode
  type: string
- container: ''
  name: author
  type: reference
- container: ''
  name: content
  type: string
- container: ''
  name: href
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: iosCfbundleversion
  type: string
- container: set
  name: platforms
  type: reference
- container: set
  name: plugins
  type: reference
- container: set
  name: preferences
  type: reference
- container: ''
  name: src
  type: string
- container: ''
  name: xmlns
  type: string
property_count: 11
provider_name: Apache Cordova
provider_slug: apache-cordova
slug: apache-cordova-config-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cordova\": \"https://cordova.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Widget\": \"cordova:Widget\",\n    \"androidVersioncode\": {\n      \"@id\": \"cordova:android-versionCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"cordova:author\",\n      \"@type\": \"@id\"\n    },\n    \"content\": {\n      \"@id\": \"cordova:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"href\": {\n      \"@id\": \"cordova:href\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"cordova:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iosCfbundleversion\": {\n      \"@id\": \"cordova:ios-CFBundleVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\
  ,\n    \"platforms\": {\n      \"@id\": \"cordova:platforms\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"plugins\": {\n      \"@id\": \"cordova:plugins\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"preferences\": {\n      \"@id\": \"cordova:preferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"src\": {\n      \"@id\": \"cordova:src\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"xmlns\": {\n      \"@id\": \"cordova:xmlns\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-cordova/refs/heads/main/json-ld/apache-cordova-config-context.jsonld
tags:
- Apache
- Cross-Platform
- Hybrid Apps
- JavaScript
- Mobile
- Open Source
- Plugins
- JSON-LD
- Linked Data
- Semantic Web
---
