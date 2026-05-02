---
api_specs:
- filename: neon-management-api-openapi.yml
  format: yaml
  label: Neon Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/openapi/neon-management-api-openapi.yml
- filename: neon-auth-webhooks-asyncapi.yml
  format: yaml
  label: Neon Auth
  slug: auth
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/asyncapi/neon-auth-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/neon-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/json-ld/neon-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Neon from Neon.
layout: jsonld
name: Neon Context
namespaces:
- prefix: neon
  uri: https://neon.com/schemas/neon/
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
  name: Branch
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Operation
  type: ''
- container: ''
  name: User
  type: ''
property_count: 7
provider_name: Neon
provider_slug: neon
slug: neon-context
source_filename: neon-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neon\": \"https://neon.com/schemas/neon/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"neon:Project\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"region_id\": \"neon:regionId\",\n        \"pg_version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"org_id\": \"neon:organizationId\",\n        \"store_passwords\": {\n          \"@id\": \"neon:storePasswords\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"active_time\": {\n          \"@id\": \"neon:activeTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cpu_used_sec\": {\n          \"@id\": \"neon:cpuUsedSeconds\",\n          \"@type\": \"xsd:integer\"\n        },\n       \
  \ \"creation_source\": \"neon:creationSource\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Branch\": {\n      \"@id\": \"neon:Branch\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"project_id\": {\n          \"@id\": \"neon:projectId\",\n          \"@type\": \"@id\"\n        },\n        \"parent_id\": {\n          \"@id\": \"neon:parentBranchId\",\n          \"@type\": \"@id\"\n        },\n        \"parent_lsn\": \"neon:parentLsn\",\n        \"parent_timestamp\": {\n          \"@id\": \"neon:parentTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"current_state\": \"neon:currentState\",\n        \"logical_size\": {\n          \"@id\": \"neon:logicalSize\",\n          \"@type\": \"\
  xsd:integer\"\n        },\n        \"primary\": {\n          \"@id\": \"neon:isPrimary\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"neon:Database\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"branch_id\": {\n          \"@id\": \"neon:branchId\",\n          \"@type\": \"@id\"\n        },\n        \"owner_name\": \"neon:ownerName\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"neon:Role\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"branch_id\": {\n          \"@id\": \"neon:branchId\",\n          \"@type\": \"@id\"\n        },\n        \"protected\": {\n          \"@id\": \"neon:isProtected\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Endpoint\": {\n      \"@id\": \"neon:Endpoint\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"host\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"project_id\": {\n          \"@id\": \"neon:projectId\",\n          \"@type\": \"@id\"\n        },\n        \"branch_id\": {\n          \"@id\": \"neon:branchId\",\n          \"@type\": \"@id\"\n        },\n        \"region_id\"\
  : \"neon:regionId\",\n        \"type\": \"neon:endpointType\",\n        \"current_state\": \"neon:currentState\",\n        \"autoscaling_limit_min_cu\": {\n          \"@id\": \"neon:autoscalingMinCu\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"autoscaling_limit_max_cu\": {\n          \"@id\": \"neon:autoscalingMaxCu\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"suspend_timeout_seconds\": {\n          \"@id\": \"neon:suspendTimeoutSeconds\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"disabled\": {\n          \"@id\": \"neon:isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Operation\": {\n      \"@id\": \"neon:Operation\",\n      \"@context\": {\n        \"id\"\
  : \"schema:identifier\",\n        \"project_id\": {\n          \"@id\": \"neon:projectId\",\n          \"@type\": \"@id\"\n        },\n        \"branch_id\": {\n          \"@id\": \"neon:branchId\",\n          \"@type\": \"@id\"\n        },\n        \"endpoint_id\": {\n          \"@id\": \"neon:endpointId\",\n          \"@type\": \"@id\"\n        },\n        \"action\": \"neon:operationAction\",\n        \"status\": \"neon:operationStatus\",\n        \"failures_count\": {\n          \"@id\": \"neon:failuresCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"neon:AuthUser\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"name\":\
  \ \"schema:name\",\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"email_verified\": {\n          \"@id\": \"neon:emailVerified\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/json-ld/neon-context.jsonld
tags:
- Databases
- Serverless
- Postgres
- Infrastructure
- Authentication
- Edge
- JSON-LD
- Linked Data
- Semantic Web
---
