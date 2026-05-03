---
api_specs:
- filename: saashub-openapi.yml
  format: yaml
  label: SaaSHub API
  slug: saashub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/openapi/saashub-openapi.yml
class_count: 7
classes:
- id
- name
- tagline
- status
- category
- categories
- pricing
context_file: json-ld/saashub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/json-ld/saashub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Saashub from SaaSHub.
layout: jsonld
name: Saashub Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: saashub
  uri: https://www.saashub.com/terms/
properties:
- container: ''
  name: Product
  type: reference
- container: ''
  name: saashubUrl
  type: reference
- container: ''
  name: websiteUrl
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: openSource
  type: boolean
- container: ''
  name: upvoteCount
  type: integer
- container: ''
  name: alternativeCount
  type: integer
property_count: 7
provider_name: SaaSHub
provider_slug: saashub
slug: saashub-context
source_filename: saashub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"saashub\": \"https://www.saashub.com/terms/\",\n\n    \"Product\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@type\": \"@id\"\n    },\n    \"id\": \"dcterms:identifier\",\n    \"name\": \"schema:name\",\n    \"tagline\": \"schema:description\",\n    \"saashubUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"websiteUrl\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    },\n    \"status\": \"schema:operatingSystem\",\n    \"category\": \"schema:applicationCategory\",\n    \"categories\": \"schema:applicationCategory\",\n    \"pricing\": \"schema:priceRange\",\n    \"license\": {\n      \"@id\": \"schema:license\",\n      \"@type\": \"@id\"\n    },\n    \"openSource\": {\n      \"@id\": \"schema:isAccessibleForFree\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"upvoteCount\": {\n      \"@id\": \"schema:interactionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alternativeCount\": {\n      \"@id\": \"saashub:alternativeCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/saashub/refs/heads/main/json-ld/saashub-context.jsonld
tags:
- Alternatives
- SaaS
- Software Discovery
- Software Catalog
- JSON-LD
- Linked Data
- Semantic Web
---
