---
class_count: 9
classes:
- ErrorResponse
- Model
- ModelDetail
- ModelList
- ModelImportRequest
- Element
- ElementList
- Relationship
- RelationshipList
context_file: json-ld/archimate-model-exchange-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/json-ld/archimate-model-exchange-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Archimate Model Exchange Api from ArchiMate.
layout: jsonld
name: Archimate Model Exchange Api Context
namespaces:
- prefix: archimate
  uri: https://archimate-org.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: elementCount
  type: integer
- container: ''
  name: relationshipCount
  type: integer
- container: ''
  name: viewCount
  type: integer
- container: ''
  name: models
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: content
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: layer
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: elements
  type: string
- container: ''
  name: sourceId
  type: string
- container: ''
  name: targetId
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: relationships
  type: string
property_count: 22
provider_name: ArchiMate
provider_slug: archimate
slug: archimate-model-exchange-api-context
source_filename: archimate-model-exchange-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"archimate\": \"https://archimate-org.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"archimate:ErrorResponse\",\n    \"message\": {\n      \"@id\": \"archimate:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"archimate:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Model\": \"archimate:Model\",\n    \"id\": {\n      \"@id\": \"archimate:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"archimate:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"archimate:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"archimate:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"archimate:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\"\
  : {\n      \"@id\": \"archimate:modifiedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ModelDetail\": \"archimate:ModelDetail\",\n    \"elementCount\": {\n      \"@id\": \"archimate:elementCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"relationshipCount\": {\n      \"@id\": \"archimate:relationshipCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"viewCount\": {\n      \"@id\": \"archimate:viewCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ModelList\": \"archimate:ModelList\",\n    \"models\": {\n      \"@id\": \"archimate:models\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"archimate:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ModelImportRequest\": \"archimate:ModelImportRequest\",\n    \"content\": {\n      \"@id\": \"archimate:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Element\": \"archimate:Element\",\n    \"type\": {\n      \"@id\": \"archimate:type\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"layer\": {\n      \"@id\": \"archimate:layer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"archimate:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ElementList\": \"archimate:ElementList\",\n    \"elements\": {\n      \"@id\": \"archimate:elements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Relationship\": \"archimate:Relationship\",\n    \"sourceId\": {\n      \"@id\": \"archimate:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetId\": {\n      \"@id\": \"archimate:targetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"archimate:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelationshipList\": \"archimate:RelationshipList\",\n    \"relationships\": {\n      \"@id\": \"archimate:relationships\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/archimate/refs/heads/main/json-ld/archimate-model-exchange-api-context.jsonld
tags:
- Enterprise Architecture
- Architecture Framework
- Modeling Language
- Business Architecture
- Technology Architecture
- Standard
- Open Group
- JSON-LD
- Linked Data
- Semantic Web
---
