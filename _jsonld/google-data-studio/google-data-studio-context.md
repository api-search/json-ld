---
api_specs:
- filename: google-data-studio-api-openapi.yml
  format: yaml
  label: Google Data Studio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/openapi/google-data-studio-api-openapi.yml
- filename: google-data-studio-linking-api-openapi.yml
  format: yaml
  label: Looker Studio Linking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/openapi/google-data-studio-linking-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-data-studio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/json-ld/google-data-studio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Data Studio from Google Data Studio.
layout: jsonld
name: Google Data Studio Context
namespaces:
- prefix: datastudio
  uri: https://developers.google.com/looker-studio/integrate/api/reference/types#
- prefix: goog
  uri: https://googleapis.com/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Report
  type: schema:CreativeWork
- container: ''
  name: DataSource
  type: schema:DataCatalog
- container: ''
  name: Permissions
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Member
  type: schema:Person
- container: ''
  name: Connector
  type: schema:SoftwareApplication
- container: ''
  name: Field
  type: schema:PropertyValueSpecification
- container: ''
  name: Visualization
  type: schema:WebApplication
- container: ''
  name: AssetType
  type: ''
property_count: 10
provider_name: Google Data Studio
provider_slug: google-data-studio
slug: google-data-studio-context
source_filename: google-data-studio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"datastudio\": \"https://developers.google.com/looker-studio/integrate/api/reference/types#\",\n    \"goog\": \"https://googleapis.com/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Asset\": {\n      \"@id\": \"datastudio:Asset\",\n      \"@context\": {\n        \"assetType\": {\n          \"@id\": \"datastudio:assetType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n      \
  \    \"@type\": \"xsd:string\"\n        },\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"trashed\": {\n          \"@id\": \"datastudio:trashed\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"datastudio:Report\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n      \
  \  },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"datastudio:DataSource\",\n      \"@type\": \"schema:DataCatalog\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n      \
  \    \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Permissions\": {\n      \"@id\": \"datastudio:Permissions\",\n      \"@context\": {\n        \"permissions\": {\n          \"@id\": \"datastudio:permissions\",\n          \"@type\": \"@id\"\n        },\n        \"etag\": {\n          \"@id\": \"goog:etag\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"datastudio:Role\",\n      \"@context\": {\n        \"VIEWER\": \"datastudio:Role/VIEWER\",\n        \"EDITOR\": \"datastudio:Role/EDITOR\",\n        \"OWNER\": \"datastudio:Role/OWNER\",\n        \"LINK_VIEWER\": \"datastudio:Role/LINK_VIEWER\",\n        \"LINK_EDITOR\": \"datastudio:Role/LINK_EDITOR\"\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"datastudio:Member\",\n      \"@type\": \"schema:Person\"\n    },\n\n    \"Connector\": {\n      \"@id\": \"datastudio:CommunityConnector\",\n      \"@type\": \"schema:SoftwareApplication\"\
  ,\n      \"@context\": {\n        \"authType\": {\n          \"@id\": \"datastudio:authType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"config\": {\n          \"@id\": \"datastudio:config\",\n          \"@type\": \"@id\"\n        },\n        \"schema\": {\n          \"@id\": \"datastudio:schema\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Field\": {\n      \"@id\": \"datastudio:Field\",\n      \"@type\": \"schema:PropertyValueSpecification\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataType\": {\n          \"@id\": \"datastudio:dataType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"semanticType\"\
  : {\n          \"@id\": \"datastudio:semanticType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"conceptType\": {\n          \"@id\": \"datastudio:conceptType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Visualization\": {\n      \"@id\": \"datastudio:CommunityVisualization\",\n      \"@type\": \"schema:WebApplication\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AssetType\": {\n      \"@id\": \"datastudio:AssetType\",\n      \"@context\": {\n        \"REPORT\": \"datastudio:AssetType/REPORT\",\n        \"DATA_SOURCE\": \"datastudio:AssetType/DATA_SOURCE\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/json-ld/google-data-studio-context.jsonld
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data
- Reporting
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
