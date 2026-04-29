---
class_count: 11
classes:
- Representation
- LibraryInput
- Element
- ElementList
- Links
- Library
- ElementInput
- LibraryList
- name
- created_date
- modified_date
context_file: json-ld/adobe-premiere-creative-cloud-libraries-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-premiere/refs/heads/main/json-ld/adobe-premiere-creative-cloud-libraries-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Premiere Creative Cloud Libraries from Adobe Premiere Pro.
layout: jsonld
name: Adobe Premiere Creative Cloud Libraries Context
namespaces:
- prefix: apc
  uri: https://developer.adobe.com/premiere/schema/
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
  name: type
  type: string
- container: ''
  name: content
  type: reference
- container: set
  name: representations
  type: string
- container: set
  name: elements
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: start
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: self
  type: reference
- container: ''
  name: totalElements
  type: integer
- container: ''
  name: links
  type: string
- container: set
  name: libraries
  type: string
property_count: 12
provider_name: Adobe Premiere Pro
provider_slug: adobe-premiere
slug: adobe-premiere-creative-cloud-libraries-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apc\": \"https://developer.adobe.com/premiere/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Representation\": \"apc:Representation\",\n    \"LibraryInput\": \"apc:LibraryInput\",\n    \"Element\": \"apc:Element\",\n    \"ElementList\": \"apc:ElementList\",\n    \"Links\": \"apc:Links\",\n    \"Library\": \"apc:Library\",\n    \"ElementInput\": \"apc:ElementInput\",\n    \"LibraryList\": \"apc:LibraryList\",\n    \"id\": {\n      \"@id\": \"apc:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"apc:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"apc:content\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"created_date\": \"schema:dateCreated\",\n    \"modified_date\": \"schema:dateModified\",\n    \"representations\"\
  : {\n      \"@id\": \"apc:representations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elements\": {\n      \"@id\": \"apc:elements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"apc:total_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"apc:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"apc:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"self\": {\n      \"@id\": \"apc:self\",\n      \"@type\": \"@id\"\n    },\n    \"totalElements\": {\n      \"@id\": \"apc:total_elements\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"links\": {\n      \"@id\": \"apc:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"libraries\": {\n      \"@id\": \"apc:libraries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-premiere/refs/heads/main/json-ld/adobe-premiere-creative-cloud-libraries-context.jsonld
tags:
- Adobe
- Automation
- Creative Cloud
- Media
- Premiere Pro
- Video Editing
- Video Production
- JSON-LD
- Linked Data
- Semantic Web
---
