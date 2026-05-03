---
class_count: 0
classes: []
context_file: json-ld/schema-design-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-design/refs/heads/main/json-ld/schema-design-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Design from Schema Design.
layout: jsonld
name: Schema Design Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: sdo
  uri: https://api-evangelist.github.io/schema-design/vocab#
properties:
- container: ''
  name: SchemaDefinition
  type: rdfs:Class
- container: ''
  name: SchemaField
  type: rdfs:Class
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
- container: ''
  name: format
  type: string
- container: set
  name: fields
  type: ''
- container: ''
  name: required
  type: boolean
- container: ''
  name: constraints
  type: reference
- container: set
  name: examples
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: schemaFormat
  type: string
- container: ''
  name: jsonSchema
  type: string
- container: ''
  name: openApiSchema
  type: string
- container: ''
  name: graphqlSchema
  type: string
- container: ''
  name: avroSchema
  type: string
- container: ''
  name: protobufSchema
  type: string
property_count: 19
provider_name: Schema Design
provider_slug: schema-design
slug: schema-design-context
source_filename: schema-design-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"sdo\": \"https://api-evangelist.github.io/schema-design/vocab#\",\n\n    \"SchemaDefinition\": {\n      \"@id\": \"sdo:SchemaDefinition\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A formal definition of the structure and constraints of a data type\"\n    },\n    \"SchemaField\": {\n      \"@id\": \"sdo:SchemaField\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A named property or attribute in a schema definition\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"format\": {\n      \"@id\": \"sdo:schemaFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"sdo:hasField\",\n      \"@container\": \"@set\"\n    },\n    \"required\": {\n      \"@id\": \"sdo:isRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"constraints\": {\n      \"@id\": \"sdo:hasConstraints\",\n      \"@type\": \"@id\"\n    },\n    \"examples\": {\n      \"@id\": \"schema:workExample\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"schemaFormat\": {\n      \"@id\": \"sdo:schemaFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonSchema\": {\n      \"@id\": \"sdo:jsonSchemaFormat\",\n      \"@type\": \"xsd:string\"\
  ,\n      \"rdfs:comment\": \"JSON Schema format (Draft 4, 7, 2019-09, 2020-12)\"\n    },\n    \"openApiSchema\": {\n      \"@id\": \"sdo:openApiSchemaFormat\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"OpenAPI Schema Object\"\n    },\n    \"graphqlSchema\": {\n      \"@id\": \"sdo:graphqlSchemaFormat\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"GraphQL SDL type definition\"\n    },\n    \"avroSchema\": {\n      \"@id\": \"sdo:avroSchemaFormat\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Apache Avro JSON schema format\"\n    },\n    \"protobufSchema\": {\n      \"@id\": \"sdo:protobufSchemaFormat\",\n      \"@type\": \"xsd:string\",\n      \"rdfs:comment\": \"Protocol Buffers .proto format\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-design/refs/heads/main/json-ld/schema-design-context.jsonld
tags:
- Schema Design
- Data Modeling
- API Design
- JSON Schema
- OpenAPI
- GraphQL
- Data Validation
- Type Systems
- JSON-LD
- Linked Data
- Semantic Web
---
