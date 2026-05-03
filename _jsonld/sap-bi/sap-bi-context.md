---
api_specs:
- filename: overview
  format: yaml
  label: SAP Analytics Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_ANALYTICS_CLOUD/overview
- filename: overview
  format: yaml
  label: SAP BusinessObjects BI Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/BOBJ_BIPLATFORM/overview
- filename: sap-bi-bw4hana-odata-openapi.yml
  format: yaml
  label: SAP BW/4HANA OData API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-bi/refs/heads/main/openapi/sap-bi-bw4hana-odata-openapi.yml
- filename: overview
  format: yaml
  label: SAP Datasphere API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/datasphere/overview
class_count: 0
classes: []
context_file: json-ld/sap-bi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-bi/refs/heads/main/json-ld/sap-bi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Bi from SAP Business Intelligence.
layout: jsonld
name: Sap Bi Context
namespaces:
- prefix: sapbi
  uri: https://api.sap.com/schemas/sap-bi/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Story
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: InfoObject
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: InfoProvider
  type: ''
- container: ''
  name: ImportJob
  type: ''
- container: ''
  name: Schedule
  type: ''
property_count: 9
provider_name: SAP Business Intelligence
provider_slug: sap-bi
slug: sap-bi-context
source_filename: sap-bi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sapbi\": \"https://api.sap.com/schemas/sap-bi/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Story\": {\n      \"@id\": \"sapbi:Story\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdBy\": \"schema:author\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedBy\": \"sapbi:modifiedBy\",\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"sapbi:publicationStatus\",\n        \"folderId\": \"sapbi:folderId\"\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"sapbi:Model\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"\
  schema:description\",\n        \"type\": \"sapbi:modelType\",\n        \"createdBy\": \"schema:author\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"sapbi:Report\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"sapbi:reportType\",\n        \"owner\": \"schema:author\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"folderId\": {\n          \"@id\": \"sapbi:folderId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"InfoObject\"\
  : {\n      \"@id\": \"sapbi:InfoObject\",\n      \"@context\": {\n        \"SI_NAME\": \"schema:name\",\n        \"SI_DESCRIPTION\": \"schema:description\",\n        \"SI_KIND\": \"sapbi:objectKind\",\n        \"SI_OWNER\": \"schema:author\",\n        \"SI_CREATION_TIME\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"SI_UPDATE_TS\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"sapbi:DataSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"sapbi:connectionType\",\n        \"status\": \"sapbi:connectionStatus\",\n        \"host\": \"sapbi:host\",\n        \"port\": {\n          \"@id\": \"sapbi:port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sslEnabled\": {\n          \"@id\": \"sapbi:sslEnabled\",\n          \"@type\"\
  : \"xsd:boolean\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"sapbi:Space\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"storageAssignment\": \"sapbi:storageAssignment\",\n        \"diskStorageQuota\": {\n          \"@id\": \"sapbi:diskStorageQuota\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"memoryStorageQuota\": {\n          \"@id\": \"sapbi:memoryStorageQuota\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"InfoProvider\": {\n      \"@id\": \"sapbi:InfoProvider\",\n      \"@context\": {\n        \"InfoProviderName\": \"schema:name\",\n        \"InfoProviderDescription\": \"schema:description\",\n       \
  \ \"InfoProviderType\": \"sapbi:infoProviderType\",\n        \"InfoArea\": \"sapbi:infoArea\",\n        \"CreatedBy\": \"schema:author\",\n        \"CreatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ImportJob\": {\n      \"@id\": \"sapbi:ImportJob\",\n      \"@context\": {\n        \"status\": \"sapbi:jobStatus\",\n        \"importType\": \"sapbi:importType\",\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedTime\": {\n          \"@id\": \"sapbi:completedTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"rowsProcessed\": {\n          \"@id\": \"sapbi:rowsProcessed\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"sapbi:Schedule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"sapbi:scheduleStatus\",\n \
  \       \"recurrenceType\": \"sapbi:recurrenceType\",\n        \"nextRunTime\": {\n          \"@id\": \"sapbi:nextRunTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"format\": \"sapbi:outputFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-bi/refs/heads/main/json-ld/sap-bi-context.jsonld
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
