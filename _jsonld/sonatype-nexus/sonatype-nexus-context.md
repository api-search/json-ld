---
api_specs:
- filename: sonatype-nexus-repository-openapi.yml
  format: yaml
  label: Nexus Repository API
  slug: nexus-repository-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/openapi/sonatype-nexus-repository-openapi.yml
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/sonatype-nexus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-ld/sonatype-nexus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sonatype Nexus from Sonatype Nexus.
layout: jsonld
name: Sonatype Nexus Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: nexus
  uri: https://help.sonatype.com/en/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Component
  type: reference
- container: ''
  name: Repository
  type: reference
- container: ''
  name: Asset
  type: reference
- container: ''
  name: format
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: online
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: checksum
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: fileSize
  type: integer
- container: set
  name: assets
  type: ''
- container: set
  name: memberNames
  type: ''
property_count: 17
provider_name: Sonatype Nexus
provider_slug: sonatype-nexus
slug: sonatype-nexus-context
source_filename: sonatype-nexus-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"nexus\": \"https://help.sonatype.com/en/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Component\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@type\": \"@id\"\n    },\n    \"Repository\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"@type\": \"@id\"\n    },\n    \"Asset\": {\n      \"@id\": \"schema:MediaObject\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"format\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"nexus:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"schema:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"online\": {\n      \"@id\": \"schema:available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checksum\": {\n      \"@id\": \"schema:checksumAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fileSize\": {\n      \"@id\": \"schema:fileSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"assets\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@set\"\n    },\n    \"memberNames\": {\n      \"@id\": \"nexus:memberNames\",\n      \"@container\": \"@set\"\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-ld/sonatype-nexus-context.jsonld
tags:
- Artifact Management
- DevOps
- Package Management
- Repository
- Maven
- npm
- Docker
- Software Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
