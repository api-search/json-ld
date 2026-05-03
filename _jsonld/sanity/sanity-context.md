---
api_specs:
- filename: sanity-openapi.yml
  format: yaml
  label: Sanity Query API
  slug: sanity-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/openapi/sanity-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sanity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/json-ld/sanity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sanity from Sanity.
layout: jsonld
name: Sanity Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sanity
  uri: https://api-evangelist.github.io/sanity/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ContentLake
  type: schema:DataCatalog
- container: ''
  name: SanityDocument
  type: schema:CreativeWork
- container: ''
  name: Dataset
  type: schema:Dataset
- container: ''
  name: Project
  type: schema:SoftwareApplication
- container: ''
  name: Webhook
  type: schema:WebAPI
- container: ''
  name: _id
  type: string
- container: ''
  name: _type
  type: string
- container: ''
  name: _createdAt
  type: dateTime
- container: ''
  name: _updatedAt
  type: dateTime
- container: ''
  name: GROQ
  type: schema:Language
- container: ''
  name: mutation
  type: schema:Action
- container: ''
  name: perspective
  type: string
property_count: 12
provider_name: Sanity
provider_slug: sanity
slug: sanity-context
source_filename: sanity-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sanity\": \"https://api-evangelist.github.io/sanity/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ContentLake\": {\n      \"@id\": \"sanity:ContentLake\",\n      \"@type\": \"schema:DataCatalog\",\n      \"schema:description\": \"Sanity's hosted content store for structured content documents\"\n    },\n\n    \"SanityDocument\": {\n      \"@id\": \"sanity:Document\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n\n    \"Dataset\": {\n      \"@id\": \"sanity:Dataset\",\n      \"@type\": \"schema:Dataset\",\n      \"schema:description\": \"A named collection of documents within a Sanity project\"\n    },\n\n    \"Project\": {\n      \"@id\": \"sanity:Project\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:description\": \"A Sanity workspace containing datasets, schemas, and configurations\"\n    },\n\n    \"Webhook\": {\n      \"@id\"\
  : \"sanity:Webhook\",\n      \"@type\": \"schema:WebAPI\",\n      \"schema:description\": \"An event-driven notification endpoint for content changes\"\n    },\n\n    \"_id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"_type\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"_createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"_updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"GROQ\": {\n      \"@id\": \"sanity:GROQ\",\n      \"@type\": \"schema:Language\",\n      \"schema:description\": \"Graph-Relational Object Queries — Sanity's content query language\"\n    },\n\n    \"mutation\": {\n      \"@id\": \"sanity:Mutation\",\n      \"@type\": \"schema:Action\"\n    },\n\n    \"perspective\": {\n      \"@id\": \"sanity:ContentPerspective\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sanity/refs/heads/main/json-ld/sanity-context.jsonld
tags:
- Headless CMS
- Content Management
- GROQ
- Real-Time
- Structured Content
- Developer Platform
- JSON-LD
- Linked Data
- Semantic Web
---
