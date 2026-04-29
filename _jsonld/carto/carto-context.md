---
class_count: 0
classes: []
context_file: json-ld/carto-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/carto/refs/heads/main/json-ld/carto-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Carto from Carto.
layout: jsonld
name: Carto Context
namespaces:
- prefix: carto
  uri: https://carto.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
properties:
- container: ''
  name: Map
  type: ''
- container: ''
  name: Layer
  type: ''
- container: ''
  name: Source
  type: ''
- container: ''
  name: Tileset
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Widget
  type: ''
- container: ''
  name: DataObservatoryDataset
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: APIAccessToken
  type: ''
property_count: 9
provider_name: Carto
provider_slug: carto
slug: carto-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"carto\": \"https://carto.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n\n    \"Map\": {\n      \"@id\": \"schema:Map\",\n      \"@context\": {\n        \"mapId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"layers\": {\n          \"@id\": \"carto:layers\",\n          \"@container\": \"@list\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Layer\": {\n      \"@id\": \"carto:Layer\",\n      \"@context\": {\n        \"layerId\": \"schema:identifier\",\n        \"source\": {\n          \"@id\": \"carto:source\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"carto:layerType\",\n        \"style\": \"carto:style\"\
  \n      }\n    },\n\n    \"Source\": {\n      \"@id\": \"carto:Source\",\n      \"@context\": {\n        \"sourceId\": \"schema:identifier\",\n        \"sourceType\": \"carto:sourceType\",\n        \"connection\": {\n          \"@id\": \"carto:connection\",\n          \"@type\": \"@id\"\n        },\n        \"table\": \"carto:tableRef\",\n        \"query\": \"carto:query\"\n      }\n    },\n\n    \"Tileset\": {\n      \"@id\": \"carto:Tileset\",\n      \"@context\": {\n        \"tilesetId\": \"schema:identifier\",\n        \"tilesetType\": \"carto:tilesetType\",\n        \"minZoom\": {\n          \"@id\": \"carto:minZoom\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"maxZoom\": {\n          \"@id\": \"carto:maxZoom\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"schema:HowTo\",\n      \"@context\": {\n        \"workflowId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"connection\":\
  \ {\n          \"@id\": \"carto:connection\",\n          \"@type\": \"@id\"\n        },\n        \"lastRun\": {\n          \"@id\": \"carto:lastRun\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Widget\": {\n      \"@id\": \"schema:WebApplication\",\n      \"@context\": {\n        \"widgetId\": \"schema:identifier\",\n        \"widgetType\": \"carto:widgetType\",\n        \"source\": {\n          \"@id\": \"carto:source\",\n          \"@type\": \"@id\"\n        },\n        \"column\": \"carto:column\"\n      }\n    },\n\n    \"DataObservatoryDataset\": {\n      \"@id\": \"schema:Dataset\",\n      \"@context\": {\n        \"datasetId\": \"schema:identifier\",\n        \"publisher\": \"schema:publisher\",\n        \"category\": \"schema:category\",\n        \"coverage\": \"schema:spatialCoverage\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"carto:Connection\",\n      \"@context\": {\n        \"connectionId\": \"schema:identifier\",\n      \
  \  \"provider\": \"schema:provider\",\n        \"databaseName\": \"carto:databaseName\"\n      }\n    },\n\n    \"APIAccessToken\": {\n      \"@id\": \"carto:APIAccessToken\",\n      \"@context\": {\n        \"tokenId\": \"schema:identifier\",\n        \"scopes\": {\n          \"@id\": \"carto:scopes\",\n          \"@container\": \"@list\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/carto/refs/heads/main/json-ld/carto-context.jsonld
tags:
- Location Intelligence
- Geospatial
- Mapping
- GIS
- SQL
- BigQuery
- Snowflake
- Data Warehouse
- JSON-LD
- Linked Data
- Semantic Web
---
