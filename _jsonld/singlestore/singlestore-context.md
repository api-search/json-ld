---
api_specs:
- filename: singlestore-data-api-openapi.yml
  format: yaml
  label: SingleStore Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-data-api-openapi.yml
- filename: singlestore-management-api-openapi.yml
  format: yaml
  label: SingleStore Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-management-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/singlestore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/json-ld/singlestore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Singlestore from SingleStore.
layout: jsonld
name: Singlestore Context
namespaces:
- prefix: singlestore
  uri: https://singlestore.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
properties:
- container: ''
  name: WorkspaceGroup
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Region
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: JobExecution
  type: ''
- container: ''
  name: Secret
  type: ''
- container: ''
  name: QueryRequest
  type: ''
- container: ''
  name: QueryResult
  type: ''
property_count: 9
provider_name: SingleStore
provider_slug: singlestore
slug: singlestore-context
source_filename: singlestore-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"singlestore\": \"https://singlestore.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"WorkspaceGroup\": {\n      \"@id\": \"singlestore:WorkspaceGroup\",\n      \"@context\": {\n        \"workspaceGroupID\": \"@id\",\n        \"name\": \"schema:name\",\n        \"state\": {\n          \"@id\": \"singlestore:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"regionID\": {\n          \"@id\": \"singlestore:region\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firewallRanges\": {\n          \"@id\": \"singlestore:firewallRanges\",\n          \"@container\": \"@set\"\n        },\n        \"allowAllTraffic\": {\n          \"@id\": \"singlestore:allowAllTraffic\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"singlestore:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Workspace\": {\n      \"@id\": \"singlestore:Workspace\",\n      \"@context\": {\n        \"workspaceID\": \"@id\",\n        \"workspaceGroupID\": {\n          \"@id\": \"singlestore:workspaceGroup\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"state\": {\n          \"@id\": \"singlestore:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"singlestore:size\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"cacheConfig\": {\n          \"@id\": \"singlestore:cacheConfig\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"singlestore:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"autoSuspend\": {\n          \"@id\": \"singlestore:autoSuspend\"\n        }\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"singlestore:Region\",\n      \"@context\": {\n        \"regionID\": \"@id\",\n        \"region\": \"schema:name\",\n        \"provider\": {\n          \"@id\": \"singlestore:cloudProvider\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"singlestore:Organization\",\n      \"@context\": {\n        \"orgID\": \"@id\",\n        \"name\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"singlestore:Job\",\n      \"@context\": {\n        \"jobID\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"completedExecutionsCount\": {\n          \"@id\": \"singlestore:completedExecutionsCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"enqueuedBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"terminatedAt\": {\n          \"@id\": \"singlestore:terminatedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"schedule\": {\n          \"@id\": \"singlestore:schedule\"\n        },\n        \"executionConfig\": {\n          \"@id\": \"singlestore:executionConfig\"\n        },\n        \"targetConfig\": {\n          \"@id\": \"singlestore:targetConfig\"\n  \
  \      }\n      }\n    },\n\n    \"JobExecution\": {\n      \"@id\": \"singlestore:JobExecution\",\n      \"@context\": {\n        \"executionID\": \"@id\",\n        \"jobID\": {\n          \"@id\": \"singlestore:job\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"singlestore:executionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"executionNumber\": {\n          \"@id\": \"singlestore:executionNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"scheduledStartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startedAt\": {\n          \"@id\": \"singlestore:startedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"finishedAt\": {\n          \"@id\": \"singlestore:finishedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"snapshotNotebookPath\": {\n          \"@id\": \"singlestore:snapshotNotebookPath\",\n   \
  \       \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Secret\": {\n      \"@id\": \"singlestore:Secret\",\n      \"@context\": {\n        \"secretID\": \"@id\",\n        \"name\": \"schema:name\",\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdatedBy\": {\n          \"@id\": \"singlestore:lastUpdatedBy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastUpdatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"QueryRequest\": {\n      \"@id\": \"singlestore:QueryRequest\",\n      \"@context\": {\n        \"sql\": {\n          \"@id\": \"singlestore:sqlStatement\",\n          \"@type\": \"xsd:string\"\n        },\n        \"database\": {\n          \"@id\": \"singlestore:database\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"args\": {\n          \"@id\": \"singlestore:queryArgs\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"QueryResult\": {\n      \"@id\": \"singlestore:QueryResult\",\n      \"@context\": {\n        \"rows\": {\n          \"@id\": \"singlestore:rows\",\n          \"@container\": \"@set\"\n        },\n        \"columns\": {\n          \"@id\": \"singlestore:columns\",\n          \"@container\": \"@list\"\n        },\n        \"rowsAffected\": {\n          \"@id\": \"singlestore:rowsAffected\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastInsertId\": {\n          \"@id\": \"singlestore:lastInsertId\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/json-ld/singlestore-context.jsonld
tags:
- Database
- SQL
- Analytics
- Cloud
- Distributed SQL
- JSON-LD
- Linked Data
- Semantic Web
---
