---
api_specs:
- filename: deno-deploy-rest-api-openapi.yml
  format: yaml
  label: Deno Deploy REST API
  slug: deploy-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-deploy-rest-api-openapi.yml
- filename: deno-deploy-v2-api-openapi.yml
  format: yaml
  label: Deno Deploy API V2
  slug: deploy-v2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-deploy-v2-api-openapi.yml
- filename: deno-subhosting-api-openapi.yml
  format: yaml
  label: Deno Subhosting API
  slug: subhosting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-subhosting-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/deno-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/json-ld/deno-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Deno from Deno.
layout: jsonld
name: Deno Context
namespaces:
- prefix: deno
  uri: https://deno.com/vocab/
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
  name: Deployment
  type: ''
- container: ''
  name: App
  type: ''
- container: ''
  name: Revision
  type: ''
- container: ''
  name: KvDatabase
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Layer
  type: ''
- container: ''
  name: EnvVar
  type: ''
property_count: 9
provider_name: Deno
provider_slug: deno
slug: deno-context
source_filename: deno-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"deno\": \"https://deno.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"deno:Project\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"organizationId\": {\n          \"@id\": \"deno:organizationId\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"deno:Deployment\",\n      \"@context\": {\n        \"\
  id\": \"@id\",\n        \"projectId\": {\n          \"@id\": \"deno:projectId\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"deno:status\",\n        \"entryPointUrl\": {\n          \"@id\": \"deno:entryPointUrl\",\n          \"@type\": \"@id\"\n        },\n        \"domains\": {\n          \"@id\": \"deno:domain\",\n          \"@container\": \"@set\"\n        },\n        \"envVars\": \"deno:envVars\",\n        \"databases\": \"deno:databases\",\n        \"assets\": \"deno:assets\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"App\": {\n      \"@id\": \"deno:App\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"slug\": \"deno:slug\",\n        \"labels\": \"deno:labels\",\n        \"layers\": {\n          \"@id\": \"deno:layer\",\n         \
  \ \"@container\": \"@set\"\n        },\n        \"env_vars\": {\n          \"@id\": \"deno:envVar\",\n          \"@container\": \"@set\"\n        },\n        \"config\": \"deno:config\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Revision\": {\n      \"@id\": \"deno:Revision\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"status\": \"deno:status\",\n        \"failure_reason\": \"deno:failureReason\",\n        \"labels\": \"deno:labels\",\n        \"layers\": {\n          \"@id\": \"deno:layer\",\n          \"@container\": \"@set\"\n        },\n        \"env_vars\": {\n          \"@id\": \"deno:envVar\",\n          \"@container\": \"@set\"\n        },\n        \"config\": \"deno:config\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"KvDatabase\": {\n      \"@id\": \"deno:KvDatabase\",\n      \"@context\": {\n        \"databaseId\": \"@id\",\n        \"description\": \"schema:description\",\n        \"kvConnect\": {\n          \"@id\": \"deno:kvConnect\",\n          \"@type\": \"@id\"\n        },\n        \"organizationId\": {\n          \"@id\": \"deno:organizationId\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"deno:Domain\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"domain\": \"schema:name\",\n        \"token\": \"\
  deno:verificationToken\",\n        \"isValidated\": {\n          \"@id\": \"deno:isValidated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"certificates\": {\n          \"@id\": \"deno:certificate\",\n          \"@container\": \"@set\"\n        },\n        \"provisioningStatus\": \"deno:provisioningStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"pro\": {\n          \"@id\": \"deno:proSubscription\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Layer\": {\n      \"@id\": \"deno:Layer\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"slug\": \"deno:slug\",\n\
  \        \"description\": \"schema:description\",\n        \"env_vars\": {\n          \"@id\": \"deno:envVar\",\n          \"@container\": \"@set\"\n        },\n        \"base_layer\": {\n          \"@id\": \"deno:baseLayer\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"EnvVar\": {\n      \"@id\": \"deno:EnvVar\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"key\": \"deno:envVarKey\",\n        \"value\": \"deno:envVarValue\",\n        \"secret\": {\n          \"@id\": \"deno:isSecret\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"contexts\": {\n          \"@id\": \"deno:context\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/json-ld/deno-context.jsonld
tags:
- Deployment
- Edge
- JavaScript
- Runtime
- Serverless
- TypeScript
- JSON-LD
- Linked Data
- Semantic Web
---
