---
class_count: 0
classes: []
context_file: json-ld/relational-data-modeling-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/relational-data-modeling/refs/heads/main/json-ld/relational-data-modeling-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Relational Data Modeling from Relational Data Modeling.
layout: jsonld
name: Relational Data Modeling Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdm
  uri: https://api-evangelist.github.io/relational-data-modeling/vocab/
properties:
- container: ''
  name: Entity
  type: reference
- container: ''
  name: Attribute
  type: reference
- container: ''
  name: ForeignKey
  type: reference
- container: ''
  name: Relationship
  type: reference
- container: ''
  name: Schema
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: dataType
  type: ''
- container: ''
  name: nullable
  type: boolean
- container: ''
  name: unique
  type: boolean
- container: ''
  name: isPrimaryKey
  type: boolean
- container: set
  name: primaryKey
  type: ''
- container: set
  name: foreignKeys
  type: ''
- container: set
  name: attributes
  type: ''
- container: ''
  name: referencedEntity
  type: ''
- container: set
  name: referencedColumns
  type: ''
- container: ''
  name: normalForm
  type: ''
- container: ''
  name: onDelete
  type: ''
- container: ''
  name: onUpdate
  type: ''
property_count: 19
provider_name: Relational Data Modeling
provider_slug: relational-data-modeling
slug: relational-data-modeling-context
source_filename: relational-data-modeling-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdm\": \"https://api-evangelist.github.io/relational-data-modeling/vocab/\",\n    \"Entity\": {\n      \"@id\": \"rdm:Entity\",\n      \"@type\": \"@id\"\n    },\n    \"Attribute\": {\n      \"@id\": \"rdm:Attribute\",\n      \"@type\": \"@id\"\n    },\n    \"ForeignKey\": {\n      \"@id\": \"rdm:ForeignKey\",\n      \"@type\": \"@id\"\n    },\n    \"Relationship\": {\n      \"@id\": \"rdm:Relationship\",\n      \"@type\": \"@id\"\n    },\n    \"Schema\": {\n      \"@id\": \"rdm:Schema\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dataType\": {\n      \"@id\": \"rdm:dataType\"\n    },\n    \"nullable\": {\n      \"@id\": \"rdm:nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"unique\": {\n     \
  \ \"@id\": \"rdm:unique\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPrimaryKey\": {\n      \"@id\": \"rdm:isPrimaryKey\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"primaryKey\": {\n      \"@id\": \"rdm:primaryKey\",\n      \"@container\": \"@set\"\n    },\n    \"foreignKeys\": {\n      \"@id\": \"rdm:hasForeignKey\",\n      \"@container\": \"@set\"\n    },\n    \"attributes\": {\n      \"@id\": \"rdm:hasAttribute\",\n      \"@container\": \"@set\"\n    },\n    \"referencedEntity\": {\n      \"@id\": \"rdm:referencedEntity\"\n    },\n    \"referencedColumns\": {\n      \"@id\": \"rdm:referencedColumns\",\n      \"@container\": \"@set\"\n    },\n    \"normalForm\": {\n      \"@id\": \"rdm:normalForm\"\n    },\n    \"onDelete\": {\n      \"@id\": \"rdm:onDelete\"\n    },\n    \"onUpdate\": {\n      \"@id\": \"rdm:onUpdate\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/relational-data-modeling/refs/heads/main/json-ld/relational-data-modeling-context.jsonld
tags:
- Data Architecture
- Database Design
- Entity Relationship
- Normalization
- SQL
- Schema Design
- Data Modeling
- JSON-LD
- Linked Data
- Semantic Web
---
