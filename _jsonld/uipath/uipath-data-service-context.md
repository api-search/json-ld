---
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
class_count: 7
classes:
- EntityQueryRequest
- EntityRecordCollection
- EntityRecordInput
- EntityRecord
- FilterGroup
- OrderByClause
- QueryFilter
context_file: json-ld/uipath-data-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-data-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Data Service from UiPath.
layout: jsonld
name: Uipath Data Service Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: filterGroup
  type: string
- container: set
  name: selectedFields
  type: string
- container: set
  name: orderBy
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: totalCount
  type: integer
- container: set
  name: value
  type: string
- container: ''
  name: nextLink
  type: reference
- container: ''
  name: Id
  type: string
- container: ''
  name: CreatedOn
  type: dateTime
- container: ''
  name: CreatedBy
  type: string
- container: ''
  name: ModifiedOn
  type: dateTime
- container: ''
  name: ModifiedBy
  type: string
- container: ''
  name: logicalOperator
  type: string
- container: set
  name: queryFilters
  type: string
- container: set
  name: filterGroups
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: descending
  type: boolean
- container: ''
  name: operator
  type: string
property_count: 19
provider_name: UiPath
provider_slug: uipath
slug: uipath-data-service-context
source_filename: uipath-data-service-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EntityQueryRequest\": \"uipath:EntityQueryRequest\",\n    \"EntityRecordCollection\": \"uipath:EntityRecordCollection\",\n    \"EntityRecordInput\": \"uipath:EntityRecordInput\",\n    \"EntityRecord\": \"uipath:EntityRecord\",\n    \"FilterGroup\": \"uipath:FilterGroup\",\n    \"OrderByClause\": \"uipath:OrderByClause\",\n    \"QueryFilter\": \"uipath:QueryFilter\",\n    \"filterGroup\": {\n      \"@id\": \"uipath:filterGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedFields\": {\n      \"@id\": \"uipath:selectedFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderBy\": {\n      \"@id\": \"uipath:orderBy\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"start\": {\n      \"@id\": \"uipath:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"uipath:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalCount\": {\n      \"@id\": \"uipath:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"value\": {\n      \"@id\": \"uipath:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"uipath:nextLink\",\n      \"@type\": \"@id\"\n    },\n    \"Id\": {\n      \"@id\": \"uipath:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedOn\": {\n      \"@id\": \"uipath:CreatedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreatedBy\": {\n      \"@id\": \"uipath:CreatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModifiedOn\": {\n      \"@id\": \"uipath:ModifiedOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ModifiedBy\": {\n      \"@id\": \"uipath:ModifiedBy\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"logicalOperator\": {\n      \"@id\": \"uipath:logicalOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryFilters\": {\n      \"@id\": \"uipath:queryFilters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterGroups\": {\n      \"@id\": \"uipath:filterGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"uipath:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descending\": {\n      \"@id\": \"uipath:descending\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"operator\": {\n      \"@id\": \"uipath:operator\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-data-service-context.jsonld
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
