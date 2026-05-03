---
api_specs:
- filename: overview
  format: yaml
  label: SAP Analytics Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/SACOpenAPI/overview
- filename: overview
  format: yaml
  label: SAP HANA Cloud Data Lake Files REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/HanaCloudDataLake/overview
- filename: overview
  format: yaml
  label: SAP Datasphere API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/Datasphere/overview
class_count: 26
classes:
- id
- name
- description
- createdTime
- modifiedTime
- createdBy
- modifiedBy
- resourceType
- visibility
- version
- owner
- active
- userName
- displayName
- roles
- groups
- models
- startDate
- endDate
- status
- assignee
- FactData
- MasterData
- Provider
- Namespace
- InfoStoreEntry
context_file: json-ld/sap-bi-tools-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-bi-tools/refs/heads/main/json-ld/sap-bi-tools-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Bi Tools from SAP BI Tools.
layout: jsonld
name: Sap Bi Tools Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sap
  uri: https://www.sap.com/ontology/
- prefix: bi
  uri: https://api-evangelist.github.io/sap-bi-tools/vocab#
properties:
- container: ''
  name: Story
  type: reference
- container: ''
  name: AnalyticsModel
  type: reference
- container: ''
  name: ContentItem
  type: reference
- container: ''
  name: CalendarEvent
  type: schema:Event
property_count: 4
provider_name: SAP BI Tools
provider_slug: sap-bi-tools
slug: sap-bi-tools-context
source_filename: sap-bi-tools-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sap\": \"https://www.sap.com/ontology/\",\n    \"bi\": \"https://api-evangelist.github.io/sap-bi-tools/vocab#\",\n\n    \"Story\": {\n      \"@id\": \"bi:Story\",\n      \"@type\": \"@id\",\n      \"comment\": \"An analytic story in SAP Analytics Cloud containing charts and visualizations\"\n    },\n    \"AnalyticsModel\": {\n      \"@id\": \"bi:AnalyticsModel\",\n      \"@type\": \"@id\",\n      \"comment\": \"A data model in SAP Analytics Cloud used as the basis for stories and reports\"\n    },\n    \"ContentItem\": {\n      \"@id\": \"bi:ContentItem\",\n      \"@type\": \"@id\",\n      \"comment\": \"A publishable and shareable artifact in the SAP Analytics Cloud Content Network\"\n    },\n    \"CalendarEvent\": {\n      \"@id\": \"bi:CalendarEvent\",\n      \"@type\": \"schema:Event\",\n      \"comment\": \"A planning calendar event or task used for collaborative planning workflows\"\
  \n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdTime\": \"schema:dateCreated\",\n    \"modifiedTime\": \"schema:dateModified\",\n    \"createdBy\": \"schema:creator\",\n    \"modifiedBy\": \"schema:editor\",\n    \"resourceType\": \"bi:resourceType\",\n    \"visibility\": \"bi:visibility\",\n    \"version\": \"schema:version\",\n    \"owner\": \"schema:maintainer\",\n    \"active\": \"bi:active\",\n    \"userName\": \"bi:userName\",\n    \"displayName\": \"schema:alternateName\",\n    \"roles\": \"bi:roles\",\n    \"groups\": \"bi:groups\",\n    \"models\": \"bi:models\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"status\": \"bi:status\",\n    \"assignee\": \"schema:participant\",\n\n    \"FactData\": \"bi:FactData\",\n    \"MasterData\": \"bi:MasterData\",\n    \"Provider\": \"bi:Provider\",\n    \"Namespace\": \"bi:Namespace\",\n    \"InfoStoreEntry\": \"bi:InfoStoreEntry\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-bi-tools/refs/heads/main/json-ld/sap-bi-tools-context.jsonld
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Reporting
- SAP
- JSON-LD
- Linked Data
- Semantic Web
---
