---
api_specs:
- filename: azure-log-analytics-query-api.yaml
  format: yaml
  label: Azure Log Analytics Query API
  slug: azure-log-analytics-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/openapi/azure-log-analytics-query-api.yaml
- filename: azure-log-analytics-management-api.yaml
  format: yaml
  label: Azure Log Analytics Management API
  slug: azure-log-analytics-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/openapi/azure-log-analytics-management-api.yaml
- filename: azure-log-analytics-ingestion-api.yaml
  format: yaml
  label: Azure Log Analytics Ingestion API
  slug: azure-log-analytics-ingestion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/openapi/azure-log-analytics-ingestion-api.yaml
class_count: 6
classes:
- QueryBody
- QueryResults
- Table
- Column
- ErrorResponse
- ErrorDetail
context_file: json-ld/azure-log-analytics-query-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-query-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Log Analytics Query Api from Azure Log Analytics.
layout: jsonld
name: Azure Log Analytics Query Api Context
namespaces:
- prefix: azure
  uri: https://learn.microsoft.com/en-us/azure/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: query
  type: string
- container: ''
  name: timespan
  type: string
- container: set
  name: workspaces
  type: string
- container: set
  name: tables
  type: reference
- container: ''
  name: name
  type: string
- container: set
  name: columns
  type: reference
- container: set
  name: rows
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: set
  name: details
  type: reference
property_count: 11
provider_name: Azure Log Analytics
provider_slug: azure-log-analytics
slug: azure-log-analytics-query-api-context
source_filename: azure-log-analytics-query-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azure\": \"https://learn.microsoft.com/en-us/azure/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"QueryBody\": \"azure:QueryBody\",\n    \"QueryResults\": \"azure:QueryResults\",\n    \"Table\": \"azure:Table\",\n    \"Column\": \"azure:Column\",\n    \"ErrorResponse\": \"azure:ErrorResponse\",\n    \"ErrorDetail\": \"azure:ErrorDetail\",\n\n    \"query\": {\n      \"@id\": \"azure:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timespan\": {\n      \"@id\": \"azure:timespan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaces\": {\n      \"@id\": \"azure:workspaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tables\": {\n      \"@id\": \"azure:tables\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\"\
  : \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columns\": {\n      \"@id\": \"azure:columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"rows\": {\n      \"@id\": \"azure:rows\",\n      \"@container\": \"@set\"\n    },\n    \"type\": {\n      \"@id\": \"azure:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"azure:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"azure:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"azure:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-query-api-context.jsonld
tags:
- Analytics
- Azure
- Cloud
- Logging
- Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
