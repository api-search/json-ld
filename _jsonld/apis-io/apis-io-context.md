---
class_count: 15
classes:
- Contact
- Meta
- Link
- Search
- Maintainer
- Property
- metaInformation
- Include
- API
- AddAPIsJSON
- APIsJSON
- email
- url
- name
- description
context_file: json-ld/apis-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/json-ld/apis-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apis Io from APIs.io.
layout: jsonld
name: Apis Io Context
namespaces:
- prefix: apio
  uri: https://apis.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: FN
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: adr
  type: string
- container: ''
  name: tel
  type: string
- container: ''
  name: X-github
  type: string
- container: ''
  name: photo
  type: string
- container: ''
  name: vCard
  type: string
- container: ''
  name: search
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: ''
  name: self
  type: string
- container: ''
  name: first
  type: string
- container: ''
  name: prev
  type: string
- container: ''
  name: next
  type: string
- container: ''
  name: last
  type: string
- container: ''
  name: meta
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: links
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: baseURL
  type: string
- container: ''
  name: humanURL
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: properties
  type: string
- container: set
  name: contact
  type: string
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: specificationVersion
  type: string
- container: set
  name: apis
  type: string
- container: set
  name: maintainers
  type: string
- container: set
  name: include
  type: string
property_count: 34
provider_name: APIs.io
provider_slug: apis-io
slug: apis-io-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apio\": \"https://apis.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Contact\": \"apio:Contact\",\n    \"Meta\": \"apio:Meta\",\n    \"Link\": \"apio:Link\",\n    \"Search\": \"apio:Search\",\n    \"Maintainer\": \"apio:Maintainer\",\n    \"Property\": \"apio:Property\",\n    \"metaInformation\": \"apio:metaInformation\",\n    \"Include\": \"apio:Include\",\n    \"API\": \"apio:API\",\n    \"AddAPIsJSON\": \"apio:AddAPIsJSON\",\n    \"APIsJSON\": \"apio:APIsJSON\",\n    \"FN\": {\n      \"@id\": \"apio:FN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"organizationName\": {\n      \"@id\": \"apio:organizationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adr\": {\n      \"@id\": \"apio:adr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tel\": {\n      \"@id\"\
  : \"apio:tel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"X-github\": {\n      \"@id\": \"apio:X-github\",\n      \"@type\": \"xsd:string\"\n    },\n    \"photo\": {\n      \"@id\": \"apio:photo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vCard\": {\n      \"@id\": \"apio:vCard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"search\": {\n      \"@id\": \"apio:search\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"apio:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"apio:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"apio:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"apio:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"self\": {\n      \"@id\": \"apio:self\",\n      \"@type\": \"xsd:string\"\n    },\n    \"first\": {\n      \"@id\": \"apio:first\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"prev\": {\n      \"@id\": \"apio:prev\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next\": {\n      \"@id\": \"apio:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last\": {\n      \"@id\": \"apio:last\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"apio:meta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"apio:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"links\": {\n      \"@id\": \"apio:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"key\": {\n      \"@id\": \"apio:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"apio:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"image\": {\n      \"@id\": \"apio:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseURL\": {\n      \"@id\": \"apio:baseURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"humanURL\"\
  : {\n      \"@id\": \"apio:humanURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"apio:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"apio:properties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contact\": {\n      \"@id\": \"apio:contact\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"apio:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"apio:modified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"specificationVersion\": {\n      \"@id\": \"apio:specificationVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apis\": {\n      \"@id\": \"apio:apis\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maintainers\": {\n      \"@id\": \"apio:maintainers\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"include\": {\n      \"@id\": \"apio:include\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/json-ld/apis-io-context.jsonld
tags:
- API Aggregation
- API Directory
- API Discovery
- API Indexing
- API Rating
- API Search
- APIs.json
- Search Engine
- JSON-LD
- Linked Data
- Semantic Web
---
