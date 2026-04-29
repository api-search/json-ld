---
class_count: 11
classes:
- id
- type
- name
- description
- organizationId
- createdBy
- numPublished
- tags
- policies
- policyDefinitionId
- configuration
context_file: json-ld/apiman-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/json-ld/apiman-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apiman from Apiman.
layout: jsonld
name: Apiman Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apiman
  uri: https://www.apiman.io/vocab/
properties:
- container: ''
  name: createdOn
  type: dateTime
property_count: 1
provider_name: Apiman
provider_slug: apiman
slug: apiman-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apiman\": \"https://www.apiman.io/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"organizationId\": \"apiman:organizationId\",\n    \"createdBy\": \"dcterms:creator\",\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numPublished\": \"apiman:numPublished\",\n    \"tags\": \"schema:keywords\",\n    \"policies\": \"apiman:policies\",\n    \"policyDefinitionId\": \"apiman:policyDefinitionId\",\n    \"configuration\": \"apiman:configuration\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/json-ld/apiman-context.jsonld
tags:
- API Gateway
- API Management
- Developer Portal
- Java
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
