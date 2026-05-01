---
api_specs:
- filename: fauna-core-http-api-openapi.yml
  format: yaml
  label: Fauna Core HTTP API
  slug: core-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/openapi/fauna-core-http-api-openapi.yml
- filename: fauna-event-streaming-asyncapi.yml
  format: yaml
  label: Fauna Event Streaming API
  slug: event-streaming-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/asyncapi/fauna-event-streaming-asyncapi.yml
- filename: fauna-graphql-api-openapi.yml
  format: yaml
  label: Fauna GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/openapi/fauna-graphql-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fauna-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/json-ld/fauna-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fauna from fauna.
layout: jsonld
name: Fauna Context
namespaces:
- prefix: fauna
  uri: https://fauna.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Document
  type: ''
- container: ''
  name: Collection
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Index
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: AccessProvider
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Query
  type: ''
- container: ''
  name: QueryResult
  type: ''
property_count: 9
provider_name: fauna
provider_slug: fauna
slug: fauna-context
source_filename: fauna-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fauna\": \"https://fauna.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Document\": {\n      \"@id\": \"fauna:Document\",\n      \"@context\": {\n        \"id\": \"fauna:id\",\n        \"coll\": \"fauna:collection\",\n        \"ts\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        },\n        \"data\": \"fauna:data\"\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"fauna:Collection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"indexes\": {\n          \"@id\": \"fauna:indexes\",\n          \"@container\": \"@set\"\n        },\n        \"constraints\": {\n          \"@id\": \"fauna:constraints\",\n          \"@container\": \"@set\"\n        },\n        \"history_days\": {\n          \"@id\": \"fauna:historyDays\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"document_ttls\": {\n          \"@id\": \"fauna:documentTTLs\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"fauna:Database\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"typechecked\": {\n          \"@id\": \"fauna:typechecked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"priority\": {\n          \"@id\": \"fauna:priority\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Index\": {\n      \"@id\": \"fauna:Index\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"terms\": {\n          \"@id\": \"fauna:terms\",\n          \"@container\": \"@list\"\n        },\n        \"values\": {\n          \"@id\": \"fauna:values\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"fauna:Role\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n  \
  \      \"privileges\": {\n          \"@id\": \"fauna:privileges\",\n          \"@container\": \"@set\"\n        },\n        \"membership\": {\n          \"@id\": \"fauna:membership\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AccessProvider\": {\n      \"@id\": \"fauna:AccessProvider\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"issuer\": {\n          \"@id\": \"fauna:issuer\",\n          \"@type\": \"@id\"\n        },\n        \"jwks_uri\": {\n          \"@id\": \"fauna:jwksUri\",\n          \"@type\": \"@id\"\n        },\n        \"roles\": {\n          \"@id\": \"fauna:roles\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"fauna:Event\",\n      \"@context\": {\n        \"type\": \"fauna:eventType\",\n        \"txn_ts\": {\n          \"@id\": \"fauna:transactionTimestamp\",\n          \"@type\": \"xsd:long\"\n        },\n        \"cursor\": \"fauna:cursor\",\n        \"data\"\
  : \"fauna:data\"\n      }\n    },\n\n    \"Query\": {\n      \"@id\": \"fauna:Query\",\n      \"@context\": {\n        \"query\": \"fauna:queryString\",\n        \"arguments\": \"fauna:arguments\"\n      }\n    },\n\n    \"QueryResult\": {\n      \"@id\": \"fauna:QueryResult\",\n      \"@context\": {\n        \"data\": \"fauna:resultData\",\n        \"txn_ts\": {\n          \"@id\": \"fauna:transactionTimestamp\",\n          \"@type\": \"xsd:long\"\n        },\n        \"stats\": \"fauna:queryStats\",\n        \"static_type\": \"fauna:staticType\",\n        \"schema_version\": {\n          \"@id\": \"fauna:schemaVersion\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fauna/refs/heads/main/json-ld/fauna-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
