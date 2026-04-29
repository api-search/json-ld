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
class_count: 5
classes:
- Workspace
- WorkspaceSku
- WorkspaceCapping
- SavedSearch
- Table
context_file: json-ld/azure-log-analytics-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Log Analytics Management Api from Azure Log Analytics.
layout: jsonld
name: Azure Log Analytics Management Api Context
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
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: provisioningState
  type: string
- container: ''
  name: retentionInDays
  type: integer
- container: ''
  name: publicNetworkAccessForIngestion
  type: string
- container: ''
  name: publicNetworkAccessForQuery
  type: string
- container: ''
  name: dailyQuotaGb
  type: double
- container: ''
  name: dataIngestionStatus
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: functionAlias
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastModifiedAt
  type: dateTime
property_count: 20
provider_name: Azure Log Analytics
provider_slug: azure-log-analytics
slug: azure-log-analytics-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azure\": \"https://learn.microsoft.com/en-us/azure/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Workspace\": \"azure:Workspace\",\n    \"WorkspaceSku\": \"azure:WorkspaceSku\",\n    \"WorkspaceCapping\": \"azure:WorkspaceCapping\",\n    \"SavedSearch\": \"azure:SavedSearch\",\n    \"Table\": \"azure:Table\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azure:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azure:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"\
  @id\": \"azure:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"azure:customer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioningState\": {\n      \"@id\": \"azure:provisioning_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionInDays\": {\n      \"@id\": \"azure:retention_in_days\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publicNetworkAccessForIngestion\": {\n      \"@id\": \"azure:public_network_access_for_ingestion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicNetworkAccessForQuery\": {\n      \"@id\": \"azure:public_network_access_for_query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dailyQuotaGb\": {\n      \"@id\": \"azure:daily_quota_gb\",\n      \"@type\": \"xsd:double\"\n    },\n    \"dataIngestionStatus\": {\n      \"@id\": \"azure:data_ingestion_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"azure:category\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"displayName\": {\n      \"@id\": \"azure:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"azure:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionAlias\": {\n      \"@id\": \"azure:function_alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-log-analytics/refs/heads/main/json-ld/azure-log-analytics-management-api-context.jsonld
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
