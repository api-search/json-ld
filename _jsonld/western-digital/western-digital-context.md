---
api_specs:
- filename: western-digital-my-cloud-home-openapi.yml
  format: yaml
  label: WD My Cloud Home API
  slug: my-cloud-home
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/western-digital/refs/heads/main/openapi/western-digital-my-cloud-home-openapi.yml
class_count: 0
classes: []
context_file: json-ld/western-digital-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/western-digital/refs/heads/main/json-ld/western-digital-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Western Digital from western-digital.
layout: jsonld
name: Western Digital Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wd
  uri: https://developer.westerndigital.com/ontology/
properties:
- container: ''
  name: FileItem
  type: reference
- container: ''
  name: fileId
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: mimeType
  type: string
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: parentId
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: modifiedTime
  type: dateTime
- container: ''
  name: thumbnailUrl
  type: reference
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: Device
  type: reference
- container: ''
  name: deviceId
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: internalURI
  type: reference
- container: ''
  name: externalURI
  type: reference
- container: ''
  name: deviceStatus
  type: string
- container: ''
  name: Share
  type: reference
- container: ''
  name: shareId
  type: string
- container: ''
  name: shareUrl
  type: reference
- container: ''
  name: expirationDate
  type: dateTime
property_count: 20
provider_name: western-digital
provider_slug: western-digital
slug: western-digital-context
source_filename: western-digital-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wd\": \"https://developer.westerndigital.com/ontology/\",\n\n    \"FileItem\": {\n      \"@id\": \"wd:FileItem\",\n      \"@type\": \"@id\"\n    },\n    \"fileId\": {\n      \"@id\": \"wd:fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mimeType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSize\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"parentId\": {\n      \"@id\": \"wd:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"thumbnailUrl\": {\n      \"@id\": \"schema:thumbnail\",\n      \"@type\": \"@id\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"Device\": {\n      \"@id\": \"wd:Device\",\n      \"@type\": \"@id\"\n    },\n    \"deviceId\": {\n      \"@id\": \"wd:deviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internalURI\": {\n      \"@id\": \"wd:internalURI\",\n      \"@type\": \"@id\"\n    },\n    \"externalURI\": {\n      \"@id\": \"wd:externalURI\",\n      \"@type\": \"@id\"\n    },\n    \"deviceStatus\": {\n      \"@id\": \"wd:status\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Share\": {\n      \"@id\": \"wd:Share\",\n      \"@type\": \"@id\"\n    },\n    \"shareId\": {\n      \"@id\": \"wd:shareId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareUrl\": {\n      \"@id\": \"schema:url\",\n  \
  \    \"@type\": \"@id\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/western-digital/refs/heads/main/json-ld/western-digital-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
