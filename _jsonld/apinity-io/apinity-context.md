---
class_count: 9
classes:
- id
- type
- name
- description
- provider
- version
- status
- compliancePolicies
- categories
context_file: json-ld/apinity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apinity-io/refs/heads/main/json-ld/apinity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apinity from Apinity.io.
layout: jsonld
name: Apinity Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apinity
  uri: https://apinity.io/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
property_count: 1
provider_name: Apinity.io
provider_slug: apinity-io
slug: apinity-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apinity\": \"https://apinity.io/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"provider\": \"schema:provider\",\n    \"version\": \"schema:version\",\n    \"status\": \"apinity:status\",\n    \"compliancePolicies\": \"apinity:compliancePolicies\",\n    \"categories\": \"schema:category\",\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apinity-io/refs/heads/main/json-ld/apinity-context.jsonld
tags:
- API Governance
- API Marketplace
- Compliance
- Discovery
- Integration Platform
- JSON-LD
- Linked Data
- Semantic Web
---
