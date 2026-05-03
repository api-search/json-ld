---
api_specs:
- filename: planetscale-platform-api-openapi.yml
  format: yaml
  label: PlanetScale Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/openapi/planetscale-platform-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/planetscale-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/json-ld/planetscale-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Planetscale from planetscale.
layout: jsonld
name: Planetscale Context
namespaces:
- prefix: ps
  uri: https://planetscale.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Branch
  type: ''
- container: ''
  name: DeployRequest
  type: ''
- container: ''
  name: Password
  type: ''
- container: ''
  name: ServiceToken
  type: ''
- container: ''
  name: Backup
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: Region
  type: ''
property_count: 10
provider_name: planetscale
provider_slug: planetscale
slug: planetscale-context
source_filename: planetscale-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ps\": \"https://planetscale.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"ps:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"plan\": \"ps:plan\",\n        \"billingEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"ps:Database\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n     \
  \   \"state\": \"ps:state\",\n        \"plan\": \"ps:plan\",\n        \"clusterSize\": \"ps:clusterSize\",\n        \"region\": \"ps:region\",\n        \"defaultBranch\": \"ps:defaultBranch\",\n        \"insightsEnabled\": \"ps:insightsEnabled\",\n        \"migrationFramework\": \"ps:migrationFramework\",\n        \"requireApprovalForDeploy\": \"ps:requireApprovalForDeploy\",\n        \"allowDataBranching\": \"ps:allowDataBranching\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"branches\": {\n          \"@id\": \"ps:branches\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Branch\": {\n      \"@id\": \"ps:Branch\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"production\": \"ps:production\",\n        \"ready\": \"ps:ready\",\n        \"shardCount\": \"ps:shardCount\",\n        \"sharded\": \"ps:sharded\",\n        \"clusterRateName\": \"ps:clusterRateName\",\n        \"region\": \"ps:region\",\n        \"parentBranch\": {\n          \"@id\": \"ps:parentBranch\",\n          \"@type\": \"@id\"\n        },\n        \"schemaLastUpdatedAt\": {\n          \"@id\": \"ps:schemaLastUpdatedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DeployRequest\": {\n      \"@id\": \"ps:DeployRequest\",\n      \"@context\": {\n        \"number\": \"schema:serialNumber\",\n        \"branch\": {\n          \"@id\": \"ps:sourceBranch\",\n          \"@type\": \"@id\"\n        },\n     \
  \   \"intoBranch\": {\n          \"@id\": \"ps:targetBranch\",\n          \"@type\": \"@id\"\n        },\n        \"state\": \"ps:state\",\n        \"approved\": \"ps:approved\",\n        \"notes\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closedAt\": {\n          \"@id\": \"ps:closedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Password\": {\n      \"@id\": \"ps:Password\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"role\": \"ps:role\",\n        \"hostname\": \"ps:hostname\",\n        \"username\": \"ps:username\",\n        \"databaseBranch\": {\n          \"@id\": \"ps:databaseBranch\",\n          \"@type\": \"@id\"\n        },\n        \"region\": \"ps:region\",\n        \"expiresAt\": {\n    \
  \      \"@id\": \"ps:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"renewable\": \"ps:renewable\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ServiceToken\": {\n      \"@id\": \"ps:ServiceToken\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"accesses\": {\n          \"@id\": \"ps:accesses\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Backup\": {\n      \"@id\": \"ps:Backup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"state\": \"ps:state\",\n        \"size\": \"schema:contentSize\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"ps:completedAt\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"ps:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"ps:Team\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"ps:slug\",\n        \"description\": \"schema:description\",\n        \"membersCount\": \"ps:membersCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"ps:Webhook\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"ps:events\",\n          \"@container\": \"@set\"\n        },\n        \"active\": \"ps:active\",\n       \
  \ \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Region\": {\n      \"@id\": \"ps:Region\",\n      \"@context\": {\n        \"slug\": \"ps:slug\",\n        \"displayName\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/planetscale/refs/heads/main/json-ld/planetscale-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
