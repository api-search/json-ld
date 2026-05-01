---
api_specs:
- filename: v1
  format: yaml
  label: ClickHouse Cloud API
  slug: clickhouse-cloud-api
  spec_type: OpenAPI
  url: https://api.clickhouse.cloud/v1
class_count: 0
classes: []
context_file: json-ld/clickhouse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clickhouse/refs/heads/main/json-ld/clickhouse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clickhouse from ClickHouse.
layout: jsonld
name: Clickhouse Context
namespaces:
- prefix: ch
  uri: https://clickhouse.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: Backup
  type: ''
property_count: 5
provider_name: ClickHouse
provider_slug: clickhouse
slug: clickhouse-context
source_filename: clickhouse-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ch\": \"https://clickhouse.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"ch:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"tier\": \"ch:tier\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Service\": {\n      \"@id\": \"ch:Service\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"provider\": \"ch:cloudProvider\",\n        \"region\": \"ch:region\",\n        \"tier\": \"ch:tier\",\n        \"state\": \"ch:state\",\n        \"endpoint\": \"schema:url\",\n        \"minReplicaMemoryGb\": \"ch:minReplicaMemoryGb\",\n        \"maxReplicaMemoryGb\"\
  : \"ch:maxReplicaMemoryGb\"\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"ch:ApiKey\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"roles\": \"ch:roles\",\n        \"expireAt\": {\n          \"@id\": \"dcterms:valid\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"role\": \"ch:role\"\n      }\n    },\n\n    \"Backup\": {\n      \"@id\": \"ch:Backup\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"status\": \"ch:status\",\n        \"serviceId\": \"ch:serviceId\",\n        \"size\": \"ch:sizeBytes\",\n        \"startedAt\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clickhouse/refs/heads/main/json-ld/clickhouse-context.jsonld
tags:
- Analytics
- Cloud Database
- Column-Oriented
- Database
- OLAP
- Open Source
- Real-Time
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
