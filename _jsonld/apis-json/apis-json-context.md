---
class_count: 9
classes:
- APIsJSON
- APIEntry
- Property
- Contact
- Include
- Overlay
- Network
- name
- description
context_file: json-ld/apis-json-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-ld/apis-json-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apis Json from APIs.json.
layout: jsonld
name: Apis Json Context
namespaces:
- prefix: apij
  uri: https://apisjson.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: aid
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: humanUrl
  type: reference
- container: ''
  name: baseURL
  type: reference
- container: ''
  name: image
  type: reference
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: specificationVersion
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: position
  type: string
- container: ''
  name: access
  type: string
- container: ''
  name: version
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: apis
  type: ''
- container: set
  name: common
  type: ''
- container: set
  name: properties
  type: ''
- container: set
  name: maintainers
  type: ''
- container: set
  name: contact
  type: ''
- container: set
  name: include
  type: ''
- container: set
  name: overlays
  type: ''
- container: set
  name: network
  type: ''
- container: ''
  name: FN
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: organizationName
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: data
  type: ''
property_count: 26
provider_name: APIs.json
provider_slug: apis-json
slug: apis-json-context
source_filename: apis-json-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apij\": \"https://apisjson.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"APIsJSON\": \"apij:APIsJSON\",\n    \"APIEntry\": \"apij:APIEntry\",\n    \"Property\": \"apij:Property\",\n    \"Contact\": \"apij:Contact\",\n    \"Include\": \"apij:Include\",\n    \"Overlay\": \"apij:Overlay\",\n    \"Network\": \"apij:Network\",\n\n    \"aid\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"humanUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"baseURL\": {\n      \"@id\": \"apij:baseURL\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"image\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"specificationVersion\": {\n      \"@id\": \"apij:specificationVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"apij:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"apij:position\",\n      \"@type\": \"xsd:string\"\n    },\n    \"access\": {\n      \"@id\": \"apij:access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apis\": {\n      \"@id\": \"apij:apis\",\n      \"@container\": \"@set\"\n    },\n\
  \    \"common\": {\n      \"@id\": \"apij:common\",\n      \"@container\": \"@set\"\n    },\n    \"properties\": {\n      \"@id\": \"apij:properties\",\n      \"@container\": \"@set\"\n    },\n    \"maintainers\": {\n      \"@id\": \"apij:maintainers\",\n      \"@container\": \"@set\"\n    },\n    \"contact\": {\n      \"@id\": \"schema:contactPoint\",\n      \"@container\": \"@set\"\n    },\n    \"include\": {\n      \"@id\": \"apij:include\",\n      \"@container\": \"@set\"\n    },\n    \"overlays\": {\n      \"@id\": \"apij:overlays\",\n      \"@container\": \"@set\"\n    },\n    \"network\": {\n      \"@id\": \"apij:network\",\n      \"@container\": \"@set\"\n    },\n    \"FN\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationName\": {\n      \"@id\": \"schema:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaType\": {\n      \"\
  @id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"apij:data\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-ld/apis-json-context.jsonld
tags:
- API Aggregation
- API Cataloging
- API Commons
- API Discovery
- API Governance
- API Operations
- Machine Readable
- Specification
- Standard
- JSON-LD
- Linked Data
- Semantic Web
---
