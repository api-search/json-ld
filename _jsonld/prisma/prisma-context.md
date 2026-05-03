---
api_specs:
- filename: openapi.json
  format: json
  label: Prisma Data Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://api.cloud.prisma.io/openapi.json
- filename: prisma-accelerate-openapi.yml
  format: yaml
  label: Prisma Accelerate API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-accelerate-openapi.yml
- filename: prisma-pulse-openapi.yml
  format: yaml
  label: Prisma Pulse API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-pulse-openapi.yml
- filename: prisma-postgres-management-openapi.yml
  format: yaml
  label: Prisma Postgres Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-postgres-management-openapi.yml
- filename: prisma-client-openapi.yml
  format: yaml
  label: Prisma Client API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-client-openapi.yml
- filename: prisma-optimize-openapi.yml
  format: yaml
  label: Prisma Optimize API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/openapi/prisma-optimize-openapi.yml
class_count: 6
classes:
- SoftwareApplication
- WebAPI
- name
- description
- email
- version
context_file: json-ld/prisma-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/json-ld/prisma-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Prisma from Prisma.
layout: jsonld
name: Prisma Context
namespaces:
- prefix: prisma
  uri: https://prisma.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: DatabaseBackup
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: WorkspaceMember
  type: ''
- container: ''
  name: CacheStrategy
  type: ''
- container: ''
  name: AccelerateInfo
  type: ''
- container: ''
  name: PulseEvent
  type: ''
- container: ''
  name: RecordingSession
  type: ''
- container: ''
  name: QueryRecommendation
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: provider
  type: reference
- container: ''
  name: documentation
  type: reference
property_count: 16
provider_name: Prisma
provider_slug: prisma
slug: prisma-context
source_filename: prisma-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"prisma\": \"https://prisma.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Workspace\": {\n      \"@id\": \"prisma:Workspace\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"slug\": \"prisma:slug\",\n        \"plan\": \"prisma:billingPlan\",\n        \"members\": \"schema:member\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"\
  @id\": \"prisma:Project\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"workspaceId\": {\n          \"@id\": \"prisma:workspace\",\n          \"@type\": \"@id\"\n        },\n        \"environments\": \"prisma:hasEnvironment\",\n        \"databases\": \"prisma:hasDatabase\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"prisma:Environment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"projectId\": {\n          \"@id\": \"prisma:project\",\n          \"@type\": \"@id\"\n        },\n        \"connectionString\": \"prisma:connectionString\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"prisma:Database\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"projectId\": {\n          \"@id\": \"prisma:project\",\n          \"@type\": \"@id\"\n        },\n        \"region\": \"prisma:deploymentRegion\",\n        \"status\": \"prisma:operationalStatus\",\n        \"engine\": \"prisma:databaseEngine\",\n        \"engineVersion\": \"schema:softwareVersion\",\n        \"connectionString\": \"prisma:connectionString\",\n        \"apiKeys\": \"prisma:hasApiKey\",\n        \"directConnection\": \"prisma:directConnection\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n   \
  \     }\n      }\n    },\n\n    \"DatabaseBackup\": {\n      \"@id\": \"prisma:DatabaseBackup\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"databaseId\": {\n          \"@id\": \"prisma:database\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"prisma:backupType\",\n        \"status\": \"prisma:operationalStatus\",\n        \"sizeBytes\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:long\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"prisma:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"prisma:Connection\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"databaseId\": {\n          \"@id\": \"prisma:database\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"prisma:connectionType\",\n      \
  \  \"connectionString\": \"prisma:connectionString\",\n        \"host\": \"schema:url\",\n        \"port\": \"prisma:port\",\n        \"username\": \"prisma:username\",\n        \"database\": \"prisma:databaseName\"\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"prisma:ApiKey\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"hint\": \"prisma:maskedValue\",\n        \"environmentId\": {\n          \"@id\": \"prisma:environment\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WorkspaceMember\": {\n      \"@id\": \"prisma:WorkspaceMember\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"userId\": {\n          \"@id\": \"prisma:user\",\n          \"@type\": \"@id\"\n        },\n        \"email\": \"schema:email\",\n        \"role\": \"prisma:memberRole\",\n        \"status\": \"prisma:memberStatus\"\
  ,\n        \"joinedAt\": {\n          \"@id\": \"prisma:joinedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CacheStrategy\": {\n      \"@id\": \"prisma:CacheStrategy\",\n      \"@context\": {\n        \"ttl\": {\n          \"@id\": \"prisma:timeToLive\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"swr\": {\n          \"@id\": \"prisma:staleWhileRevalidate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": \"prisma:cacheTag\"\n      }\n    },\n\n    \"AccelerateInfo\": {\n      \"@id\": \"prisma:AccelerateInfo\",\n      \"@context\": {\n        \"cacheStatus\": \"prisma:cacheStatus\",\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"region\": \"prisma:edgeRegion\",\n        \"requestId\": \"prisma:requestIdentifier\",\n        \"signature\": \"prisma:responseSignature\"\n      }\n    },\n\n    \"PulseEvent\": {\n      \"@id\": \"prisma:PulseEvent\"\
  ,\n      \"@context\": {\n        \"id\": \"@id\",\n        \"action\": \"prisma:eventAction\",\n        \"modelName\": \"prisma:modelName\",\n        \"created\": \"prisma:createdRecord\",\n        \"after\": \"prisma:afterState\",\n        \"before\": \"prisma:beforeState\",\n        \"deleted\": \"prisma:deletedRecord\"\n      }\n    },\n\n    \"RecordingSession\": {\n      \"@id\": \"prisma:RecordingSession\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"status\": \"prisma:sessionStatus\",\n        \"databaseProvider\": \"prisma:databaseProvider\",\n        \"queryCount\": {\n          \"@id\": \"prisma:queryCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalDuration\": {\n          \"@id\": \"prisma:totalDuration\",\n          \"@type\": \"xsd:float\"\n        },\n        \"startedAt\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endedAt\": {\n \
  \         \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"QueryRecommendation\": {\n      \"@id\": \"prisma:QueryRecommendation\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"severity\": \"prisma:severity\",\n        \"category\": \"prisma:recommendationCategory\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"affectedQueries\": {\n          \"@id\": \"prisma:affectedQuery\",\n          \"@type\": \"@id\"\n        },\n        \"suggestedAction\": \"prisma:suggestedAction\",\n        \"estimatedImpact\": \"prisma:estimatedImpact\"\n      }\n    },\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"WebAPI\": \"schema:WebAPI\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"version\": \"schema:version\"\
  ,\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"@id\"\n    },\n    \"documentation\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/prisma/refs/heads/main/json-ld/prisma-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
