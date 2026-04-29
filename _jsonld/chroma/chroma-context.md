---
api_specs:
- filename: chroma-server-api-openapi.yml
  format: yaml
  label: Chroma Server API
  slug: server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/openapi/chroma-server-api-openapi.yml
- filename: chroma-cloud-api-openapi.yml
  format: yaml
  label: Chroma Cloud API
  slug: cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/openapi/chroma-cloud-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/chroma-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/json-ld/chroma-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chroma from Chroma.
layout: jsonld
name: Chroma Context
namespaces:
- prefix: chroma
  uri: https://trychroma.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Tenant
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Collection
  type: ''
- container: ''
  name: Record
  type: ''
- container: ''
  name: Embedding
  type: ''
- container: ''
  name: QueryResult
  type: ''
property_count: 6
provider_name: Chroma
provider_slug: chroma
slug: chroma-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chroma\": \"https://trychroma.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Tenant\": {\n      \"@id\": \"chroma:Tenant\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"chroma:Database\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"tenant\": {\n          \"@id\": \"chroma:tenant\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"chroma:Collection\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"metadata\": \"chroma:metadata\",\n        \"tenant\": {\n          \"@id\": \"chroma:tenant\",\n          \"@type\": \"@id\"\n        },\n        \"database\": {\n   \
  \       \"@id\": \"chroma:database\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Record\": {\n      \"@id\": \"chroma:Record\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"embedding\": \"chroma:embedding\",\n        \"document\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metadata\": \"chroma:metadata\",\n        \"uri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Embedding\": {\n      \"@id\": \"chroma:Embedding\",\n      \"@context\": {\n        \"values\": {\n          \"@id\": \"chroma:values\",\n          \"@container\": \"@list\"\n        },\n        \"dimension\": {\n          \"@id\": \"chroma:dimension\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"QueryResult\": {\n      \"@id\": \"chroma:QueryResult\",\n      \"@context\": {\n        \"ids\": {\n          \"@id\": \"chroma:ids\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"embeddings\": {\n          \"@id\": \"chroma:embeddings\",\n          \"@container\": \"@set\"\n        },\n        \"documents\": {\n          \"@id\": \"chroma:documents\",\n          \"@container\": \"@set\"\n        },\n        \"metadatas\": {\n          \"@id\": \"chroma:metadatas\",\n          \"@container\": \"@set\"\n        },\n        \"distances\": {\n          \"@id\": \"chroma:distances\",\n          \"@container\": \"@list\"\n        },\n        \"uris\": {\n          \"@id\": \"chroma:uris\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chroma/refs/heads/main/json-ld/chroma-context.jsonld
tags:
- AI
- AI Native
- Apache 2.0
- Cloud
- Embeddings
- Hybrid Search
- JavaScript
- LLM
- Machine Learning
- Multi-Modal
- Open Source
- Python
- RAG
- Retrieval
- SDK
- Search
- Serverless
- TypeScript
- Vector Database
- JSON-LD
- Linked Data
- Semantic Web
---
