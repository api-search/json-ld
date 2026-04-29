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
class_count: 3
classes:
- LogEntry
- DataCollectionRule
- StreamDeclaration
context_file: json-ld/azure-log-analytics-ingestion-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-ingestion-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Log Analytics Ingestion Api from Azure Log Analytics.
layout: jsonld
name: Azure Log Analytics Ingestion Api Context
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
  name: TimeGenerated
  type: dateTime
- container: ''
  name: Computer
  type: string
- container: ''
  name: AdditionalContext
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: workspaceResourceId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: transformKql
  type: string
- container: ''
  name: outputStream
  type: string
property_count: 10
provider_name: Azure Log Analytics
provider_slug: azure-log-analytics
slug: azure-log-analytics-ingestion-api-context
source_filename: azure-log-analytics-ingestion-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azure\": \"https://learn.microsoft.com/en-us/azure/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"LogEntry\": \"azure:LogEntry\",\n    \"DataCollectionRule\": \"azure:DataCollectionRule\",\n    \"StreamDeclaration\": \"azure:StreamDeclaration\",\n\n    \"TimeGenerated\": {\n      \"@id\": \"azure:time_generated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Computer\": {\n      \"@id\": \"azure:computer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdditionalContext\": {\n      \"@id\": \"azure:additional_context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azure:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"azure:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceResourceId\": {\n      \"@id\": \"azure:workspace_resource_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azure:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transformKql\": {\n      \"@id\": \"azure:transform_kql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputStream\": {\n      \"@id\": \"azure:output_stream\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-ingestion-api-context.jsonld
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
