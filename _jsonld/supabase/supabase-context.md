---
api_specs:
- filename: supabase-management-api-openapi.yml
  format: yaml
  label: Supabase Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-management-api-openapi.yml
- filename: supabase-auth-api-openapi.yml
  format: yaml
  label: Supabase Auth API
  slug: auth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-auth-api-openapi.yml
- filename: supabase-storage-api-openapi.yml
  format: yaml
  label: Supabase Storage API
  slug: storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-storage-api-openapi.yml
- filename: supabase-database-rest-api-openapi.yml
  format: yaml
  label: Supabase Database REST API
  slug: database-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-database-rest-api-openapi.yml
- filename: supabase-edge-functions-api-openapi.yml
  format: yaml
  label: Supabase Edge Functions API
  slug: edge-functions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-edge-functions-api-openapi.yml
- filename: supabase-realtime-api-asyncapi.yml
  format: yaml
  label: Supabase Realtime API
  slug: realtime-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/asyncapi/supabase-realtime-api-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/supabase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/json-ld/supabase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Supabase from Supabase.
layout: jsonld
name: Supabase Context
namespaces:
- prefix: supabase
  uri: https://supabase.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: StorageBucket
  type: ''
- container: ''
  name: StorageObject
  type: ''
- container: ''
  name: EdgeFunction
  type: ''
- container: ''
  name: RealtimeChannel
  type: ''
- container: ''
  name: Secret
  type: ''
property_count: 9
provider_name: Supabase
provider_slug: supabase
slug: supabase-context
source_filename: supabase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"supabase\": \"https://supabase.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"supabase:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"region\": \"supabase:region\",\n        \"status\": \"supabase:projectStatus\",\n        \"ref\": \"supabase:projectRef\",\n        \"plan\": \"supabase:billingPlan\",\n        \"database\": {\n          \"@id\": \"supabase:database\",\n          \"@type\": \"@id\"\n        },\n        \"organization\": {\n          \"@id\": \"schema:memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"apiUrl\": {\n          \"@id\": \"supabase:apiUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n     \
  \     \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"supabase:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"supabase:slug\",\n        \"billingEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"projects\": {\n          \"@id\": \"supabase:hasProject\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"supabase:User\",\n      \"@context\": {\n        \"email\": \"schema:email\"\
  ,\n        \"phone\": \"schema:telephone\",\n        \"role\": \"supabase:userRole\",\n        \"emailConfirmedAt\": {\n          \"@id\": \"supabase:emailConfirmedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"phoneConfirmedAt\": {\n          \"@id\": \"supabase:phoneConfirmedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSignInAt\": {\n          \"@id\": \"supabase:lastSignInAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"appMetadata\": \"supabase:appMetadata\",\n        \"userMetadata\": \"supabase:userMetadata\",\n        \"identities\": {\n          \"@id\": \"supabase:hasIdentity\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n  \
  \  \"Database\": {\n      \"@id\": \"supabase:Database\",\n      \"@context\": {\n        \"host\": \"supabase:host\",\n        \"port\": \"supabase:port\",\n        \"version\": \"schema:softwareVersion\",\n        \"sslEnforced\": \"supabase:sslEnforced\"\n      }\n    },\n\n    \"StorageBucket\": {\n      \"@id\": \"supabase:StorageBucket\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"isPublic\": \"supabase:isPublic\",\n        \"fileSizeLimit\": \"supabase:fileSizeLimit\",\n        \"allowedMimeTypes\": \"supabase:allowedMimeTypes\",\n        \"objects\": {\n          \"@id\": \"supabase:containsObject\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"StorageObject\": {\n      \"@id\": \"supabase:StorageObject\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"bucket\"\
  : {\n          \"@id\": \"supabase:inBucket\",\n          \"@type\": \"@id\"\n        },\n        \"mimeType\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"publicUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastAccessedAt\": {\n          \"@id\": \"supabase:lastAccessedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EdgeFunction\": {\n      \"@id\": \"supabase:EdgeFunction\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"supabase:slug\",\n        \"status\": \"supabase:functionStatus\",\n        \"version\": \"schema:softwareVersion\",\n        \"verifyJwt\": \"supabase:verifyJwt\",\n        \"invokeUrl\": {\n          \"@id\": \"supabase:invokeUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RealtimeChannel\": {\n      \"@id\": \"supabase:RealtimeChannel\",\n      \"@context\": {\n        \"topic\": \"supabase:channelTopic\",\n        \"broadcastEnabled\": \"supabase:broadcastEnabled\",\n        \"presenceEnabled\": \"supabase:presenceEnabled\",\n        \"postgresChangesEnabled\": \"supabase:postgresChangesEnabled\"\n      }\n    },\n\n    \"Secret\": {\n      \"@id\": \"supabase:Secret\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/json-ld/supabase-context.jsonld
tags:
- Backend As A Service
- PostgreSQL
- Open Source
- Authentication
- Real Time
- Storage
- Edge Functions
- Database
- JSON-LD
- Linked Data
- Semantic Web
---
