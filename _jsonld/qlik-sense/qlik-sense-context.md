---
api_specs:
- filename: qlik-sense-cloud-rest-api-openapi.yml
  format: yaml
  label: Qlik Cloud Platform REST API
  slug: qlik-cloud-platform-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/openapi/qlik-sense-cloud-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/qlik-sense-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/json-ld/qlik-sense-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Qlik Sense from Qlik Sense.
layout: jsonld
name: Qlik Sense Context
namespaces:
- prefix: qlik
  uri: https://qlik.dev/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: QlikApp
  type: ''
- container: ''
  name: QlikSpace
  type: ''
- container: ''
  name: QlikReload
  type: ''
- container: ''
  name: QlikSpaceAssignment
  type: ''
- container: ''
  name: QlikTenant
  type: ''
- container: ''
  name: QlikDataConnection
  type: ''
property_count: 6
provider_name: Qlik Sense
provider_slug: qlik-sense
slug: qlik-sense-context
source_filename: qlik-sense-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"qlik\": \"https://qlik.dev/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"QlikApp\": {\n      \"@id\": \"qlik:QlikApp\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thumbnail\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"lastReloadTime\": {\n          \"@id\": \"qlik:lastReloadTime\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"qlik:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"published\": {\n          \"@id\": \"qlik:published\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"publishTime\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hasSectionAccess\": {\n          \"@id\": \"qlik:hasSectionAccess\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDirectQueryMode\": {\n          \"@id\": \"qlik:isDirectQueryMode\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"encrypted\"\
  : {\n          \"@id\": \"qlik:encrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"originAppId\": {\n          \"@id\": \"dcterms:source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spaceId\": {\n          \"@id\": \"qlik:spaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tenantId\": {\n          \"@id\": \"qlik:tenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"qlik:usage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dynamicColor\": {\n          \"@id\": \"qlik:dynamicColor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"space\": {\n          \"@id\": \"qlik:space\",\n          \"@type\": \"@id\"\n        },\n        \"reload\": {\n          \"@id\": \"qlik:reload\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"QlikSpace\": {\n      \"@id\": \"qlik:QlikSpace\",\n      \"@context\": {\n        \"id\": {\n          \"@id\"\
  : \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"qlik:spaceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"qlik:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tenantId\": {\n          \"@id\": \"qlik:tenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  assignments\": {\n          \"@id\": \"qlik:assignments\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"QlikReload\": {\n      \"@id\": \"qlik:QlikReload\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appId\": {\n          \"@id\": \"qlik:appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tenantId\": {\n          \"@id\": \"qlik:tenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userId\": {\n          \"@id\": \"qlik:userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"qlik:reloadType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"qlik:reloadStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partial\": {\n          \"@id\": \"qlik:partial\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"log\": {\n          \"@id\": \"qlik:reloadLog\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startTime\": {\n          \"@id\": \"qlik:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"qlik:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"engineTime\": {\n          \"@id\": \"qlik:engineTime\",\n          \"@type\": \"xsd:duration\"\n        }\n      }\n    },\n\n    \"QlikSpaceAssignment\": {\n      \"@id\": \"qlik:QlikSpaceAssignment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"qlik:assigneeType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"assigneeId\": {\n          \"@id\": \"qlik:assigneeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"roles\": {\n          \"@id\": \"qlik:roles\",\n          \"@container\": \"@set\"\n        },\n        \"spaceId\": {\n          \"@id\": \"qlik:spaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"QlikTenant\": {\n      \"@id\": \"qlik:QlikTenant\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hostnames\": {\n          \"@id\": \"qlik:hostnames\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": {\n          \"@id\": \"qlik:tenantStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"QlikDataConnection\": {\n      \"@id\": \"qlik:QlikDataConnection\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"qlik:connectionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spaceId\": {\n          \"@id\": \"qlik:spaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"qlik:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\"\
  : \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/json-ld/qlik-sense-context.jsonld
tags:
- Analytics
- Business Intelligence
- Cloud
- Data Integration
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
