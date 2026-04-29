---
api_specs:
- filename: teradata-querygrid-manager-api.yaml
  format: yaml
  label: Teradata QueryGrid Manager API
  slug: querygrid-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-querygrid-manager-api.yaml
- filename: teradata-query-service-api.yaml
  format: yaml
  label: Teradata Query Service API
  slug: query-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/openapi/teradata-query-service-api.yaml
class_count: 4
classes:
- QuerySystem
- Session
- QueryRequest
- QueryResult
context_file: json-ld/teradata-query-service-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/json-ld/teradata-query-service-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Teradata Query Service Api from Teradata.
layout: jsonld
name: Teradata Query Service Api Context
namespaces:
- prefix: td
  uri: https://developer.teradata.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: system
  type: string
- container: ''
  name: database
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: queryId
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: rowCount
  type: integer
- container: set
  name: columns
  type: ''
- container: set
  name: rows
  type: ''
property_count: 13
provider_name: Teradata
provider_slug: teradata
slug: teradata-query-service-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"td\": \"https://developer.teradata.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"QuerySystem\": \"td:QuerySystem\",\n    \"Session\": \"td:Session\",\n    \"QueryRequest\": \"td:QueryRequest\",\n    \"QueryResult\": \"td:QueryResult\",\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"host\": { \"@id\": \"td:host\", \"@type\": \"xsd:string\" },\n    \"port\": { \"@id\": \"td:port\", \"@type\": \"xsd:integer\" },\n    \"status\": { \"@id\": \"td:status\", \"@type\": \"xsd:string\" },\n    \"sessionId\": { \"@id\": \"td:sessionId\", \"@type\": \"xsd:string\" },\n    \"system\": { \"@id\": \"td:system\", \"@type\": \"xsd:string\" },\n    \"database\": { \"@id\": \"td:database\", \"@type\": \"xsd:string\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"\
  \ },\n    \"queryId\": { \"@id\": \"td:queryId\", \"@type\": \"xsd:string\" },\n    \"query\": { \"@id\": \"td:query\", \"@type\": \"xsd:string\" },\n    \"rowCount\": { \"@id\": \"td:rowCount\", \"@type\": \"xsd:integer\" },\n    \"columns\": { \"@id\": \"td:columns\", \"@container\": \"@set\" },\n    \"rows\": { \"@id\": \"td:rows\", \"@container\": \"@set\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/teradata/refs/heads/main/json-ld/teradata-query-service-api-context.jsonld
tags:
- Analytics
- Cloud
- Data Management
- Data Warehousing
- Database
- Enterprise
- Machine Learning
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
