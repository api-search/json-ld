---
class_count: 0
classes: []
context_file: json-ld/schema-evolution-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-evolution/refs/heads/main/json-ld/schema-evolution-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Evolution from Schema Evolution.
layout: jsonld
name: Schema Evolution Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: se
  uri: https://api-evangelist.github.io/schema-evolution/vocab#
properties:
- container: ''
  name: SchemaChange
  type: rdfs:Class
- container: ''
  name: SchemaVersion
  type: rdfs:Class
- container: ''
  name: CompatibilityRule
  type: rdfs:Class
- container: ''
  name: schemaName
  type: string
- container: ''
  name: fromVersion
  type: string
- container: ''
  name: toVersion
  type: string
- container: ''
  name: changeType
  type: string
- container: ''
  name: compatibilityImpact
  type: string
- container: ''
  name: fieldPath
  type: string
- container: ''
  name: migrationRequired
  type: boolean
- container: ''
  name: migrationScript
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: author
  type: string
- container: ''
  name: backwardCompatible
  type: ''
- container: ''
  name: forwardCompatible
  type: ''
- container: ''
  name: fullyCompatible
  type: ''
- container: ''
  name: breakingChange
  type: ''
property_count: 17
provider_name: Schema Evolution
provider_slug: schema-evolution
slug: schema-evolution-context
source_filename: schema-evolution-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"se\": \"https://api-evangelist.github.io/schema-evolution/vocab#\",\n\n    \"SchemaChange\": {\n      \"@id\": \"se:SchemaChange\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A versioned change to a data schema\"\n    },\n    \"SchemaVersion\": {\n      \"@id\": \"se:SchemaVersion\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A specific version of a schema definition\"\n    },\n    \"CompatibilityRule\": {\n      \"@id\": \"se:CompatibilityRule\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A rule governing which schema changes are permitted\"\n    },\n\n    \"schemaName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromVersion\": {\n      \"@id\": \"se:fromVersion\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"toVersion\": {\n      \"@id\": \"se:toVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeType\": {\n      \"@id\": \"se:changeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compatibilityImpact\": {\n      \"@id\": \"se:compatibilityImpact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldPath\": {\n      \"@id\": \"se:fieldPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationRequired\": {\n      \"@id\": \"se:migrationRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"migrationScript\": {\n      \"@id\": \"se:migrationScript\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backwardCompatible\": {\n      \"@id\": \"se:BackwardCompatible\",\n      \"rdfs:comment\": \"New schema can read data written with old schema\"\
  \n    },\n    \"forwardCompatible\": {\n      \"@id\": \"se:ForwardCompatible\",\n      \"rdfs:comment\": \"Old schema can read data written with new schema\"\n    },\n    \"fullyCompatible\": {\n      \"@id\": \"se:FullyCompatible\",\n      \"rdfs:comment\": \"Both backward and forward compatible\"\n    },\n    \"breakingChange\": {\n      \"@id\": \"se:BreakingChange\",\n      \"rdfs:comment\": \"Schema change that breaks compatibility\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-evolution/refs/heads/main/json-ld/schema-evolution-context.jsonld
tags:
- Schema Evolution
- Backward Compatibility
- Forward Compatibility
- API Versioning
- Breaking Changes
- Schema Registry
- Data Migration
- Kafka
- JSON-LD
- Linked Data
- Semantic Web
---
