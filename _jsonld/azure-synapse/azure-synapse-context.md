---
class_count: 7
classes:
- Workspace
- WorkspaceInfoListResult
- SqlPool
- SqlPoolInfoListResult
- BigDataPool
- BigDataPoolResourceInfoListResult
- name
context_file: json-ld/azure-synapse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/json-ld/azure-synapse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Synapse from Azure Synapse Analytics.
layout: jsonld
name: Azure Synapse Context
namespaces:
- prefix: azuresynapse
  uri: https://azure.microsoft.com/azure-synapse/schema/
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
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: properties
  type: reference
- container: set
  name: value
  type: string
- container: ''
  name: nextLink
  type: string
- container: ''
  name: sku
  type: reference
property_count: 8
provider_name: Azure Synapse Analytics
provider_slug: azure-synapse
slug: azure-synapse-context
source_filename: azure-synapse-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azuresynapse\": \"https://azure.microsoft.com/azure-synapse/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Workspace\": \"azuresynapse:Workspace\",\n    \"WorkspaceInfoListResult\": \"azuresynapse:WorkspaceInfoListResult\",\n    \"SqlPool\": \"azuresynapse:SqlPool\",\n    \"SqlPoolInfoListResult\": \"azuresynapse:SqlPoolInfoListResult\",\n    \"BigDataPool\": \"azuresynapse:BigDataPool\",\n    \"BigDataPoolResourceInfoListResult\": \"azuresynapse:BigDataPoolResourceInfoListResult\",\n    \"id\": {\n      \"@id\": \"azuresynapse:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"azuresynapse:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azuresynapse:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  tags\": {\n      \"@id\": \"azuresynapse:tags\",\n      \"@type\": \"@id\"\n    },\n    \"properties\": {\n      \"@id\": \"azuresynapse:properties\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"azuresynapse:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azuresynapse:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"azuresynapse:sku\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-synapse/refs/heads/main/json-ld/azure-synapse-context.jsonld
tags:
- Analytics
- Apache Spark
- Big Data
- Data Warehouse
- ETL
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
