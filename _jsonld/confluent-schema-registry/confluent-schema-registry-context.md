---
api_specs:
- filename: schema-registry.yml
  format: yaml
  label: Confluent Schema Registry REST API
  slug: schema-registry-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/openapi/schema-registry.yml
class_count: 0
classes: []
context_file: json-ld/confluent-schema-registry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/json-ld/confluent-schema-registry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Confluent Schema Registry from Confluent Schema Registry.
layout: jsonld
name: Confluent Schema Registry Context
namespaces:
- prefix: schemaregistry
  uri: https://docs.confluent.io/platform/current/schema-registry/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Subject
  type: ''
- container: ''
  name: Schema
  type: ''
- container: ''
  name: SchemaReference
  type: ''
- container: ''
  name: Config
  type: ''
- container: ''
  name: Mode
  type: ''
- container: ''
  name: CompatibilityLevel
  type: '@vocab'
- container: ''
  name: SchemaType
  type: '@vocab'
- container: ''
  name: Context
  type: ''
- container: ''
  name: Exporter
  type: ''
- container: ''
  name: ErrorMessage
  type: ''
property_count: 10
provider_name: Confluent Schema Registry
provider_slug: confluent-schema-registry
slug: confluent-schema-registry-context
source_filename: confluent-schema-registry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schemaregistry\": \"https://docs.confluent.io/platform/current/schema-registry/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Subject\": {\n      \"@id\": \"schemaregistry:Subject\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"compatibilityLevel\": \"schemaregistry:compatibilityLevel\",\n        \"versions\": {\n          \"@id\": \"schemaregistry:versions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Schema\": {\n      \"@id\": \"schemaregistry:Schema\",\n      \"@context\": {\n        \"id\": \"schemaregistry:id\",\n        \"version\": \"schemaregistry:version\",\n        \"subject\": \"schemaregistry:subject\",\n        \"schemaType\": \"schemaregistry:schemaType\",\n        \"schema\": \"schemaregistry:schema\",\n        \"references\": {\n          \"@id\"\
  : \"schemaregistry:references\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SchemaReference\": {\n      \"@id\": \"schemaregistry:SchemaReference\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"subject\": \"schemaregistry:subject\",\n        \"version\": \"schemaregistry:version\"\n      }\n    },\n\n    \"Config\": {\n      \"@id\": \"schemaregistry:Config\",\n      \"@context\": {\n        \"compatibility\": \"schemaregistry:compatibility\",\n        \"compatibilityGroup\": \"schemaregistry:compatibilityGroup\",\n        \"normalize\": \"schemaregistry:normalize\",\n        \"validateFields\": \"schemaregistry:validateFields\"\n      }\n    },\n\n    \"Mode\": {\n      \"@id\": \"schemaregistry:Mode\",\n      \"@context\": {\n        \"mode\": \"schemaregistry:mode\"\n      }\n    },\n\n    \"CompatibilityLevel\": {\n      \"@id\": \"schemaregistry:CompatibilityLevel\",\n      \"@type\": \"@vocab\",\n      \"@vocab\": \"schemaregistry:compatibilityLevel#\"\
  \n    },\n\n    \"SchemaType\": {\n      \"@id\": \"schemaregistry:SchemaType\",\n      \"@type\": \"@vocab\",\n      \"@vocab\": \"schemaregistry:schemaType#\"\n    },\n\n    \"Context\": {\n      \"@id\": \"schemaregistry:Context\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Exporter\": {\n      \"@id\": \"schemaregistry:Exporter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"subjects\": {\n          \"@id\": \"schemaregistry:subjects\",\n          \"@container\": \"@set\"\n        },\n        \"contextType\": \"schemaregistry:contextType\",\n        \"context\": \"schemaregistry:context\",\n        \"config\": \"schemaregistry:config\"\n      }\n    },\n\n    \"ErrorMessage\": {\n      \"@id\": \"schemaregistry:ErrorMessage\",\n      \"@context\": {\n        \"errorCode\": \"schemaregistry:errorCode\",\n        \"message\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/confluent-schema-registry/refs/heads/main/json-ld/confluent-schema-registry-context.jsonld
tags:
- Apache Kafka
- Avro
- Compatibility
- Confluent
- Data Governance
- Data Streaming
- JSON Schema
- Open Source
- Protobuf
- REST
- Schema Evolution
- Schema Registry
- JSON-LD
- Linked Data
- Semantic Web
---
