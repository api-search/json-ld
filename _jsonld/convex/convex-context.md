---
api_specs:
- filename: convex-http-api-openapi.yml
  format: yaml
  label: Convex HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/openapi/convex-http-api-openapi.yml
- filename: convex-management-api-openapi.yml
  format: yaml
  label: Convex Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/openapi/convex-management-api-openapi.yml
- filename: convex-deployment-platform-api-openapi.yml
  format: yaml
  label: Convex Deployment Platform API
  slug: deployment-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/openapi/convex-deployment-platform-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/convex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/json-ld/convex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Convex from Convex.
layout: jsonld
name: Convex Context
namespaces:
- prefix: convex
  uri: https://convex.dev/vocab/
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
  name: Deployment
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Function
  type: ''
- container: ''
  name: DatabaseRecord
  type: ''
- container: ''
  name: EnvironmentVariable
  type: ''
- container: ''
  name: CustomDomain
  type: ''
- container: ''
  name: DeployKey
  type: ''
- container: ''
  name: ScheduledFunction
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: TeamMember
  type: ''
property_count: 10
provider_name: Convex
provider_slug: convex
slug: convex-context
source_filename: convex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"convex\": \"https://convex.dev/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"Deployment\": {\n      \"@id\": \"convex:Deployment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"deployment_type\": {\n          \"@id\": \"convex:deploymentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"deployment_class\": {\n          \"@id\": \"convex:deploymentClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region\": {\n          \"@id\": \"convex:region\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"project_id\": {\n          \"@id\": \"convex:project\",\n          \"\
  @type\": \"@id\"\n        },\n        \"environment_variables\": {\n          \"@id\": \"convex:environmentVariables\",\n          \"@container\": \"@set\"\n        },\n        \"custom_domains\": {\n          \"@id\": \"convex:customDomains\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"convex:Project\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"slug\": {\n          \"@id\": \"convex:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"team_id\": {\n          \"@id\": \"convex:team\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Function\": {\n      \"@id\": \"convex:Function\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"convex:functionPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"function_type\": {\n          \"@id\": \"convex:functionType\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"args\": {\n          \"@id\": \"convex:arguments\"\n        }\n      }\n    },\n\n    \"DatabaseRecord\": {\n      \"@id\": \"convex:DatabaseRecord\",\n      \"@context\": {\n        \"_id\": \"@id\",\n        \"_creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"EnvironmentVariable\": {\n      \"@id\": \"convex:EnvironmentVariable\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CustomDomain\": {\n      \"@id\": \"convex:CustomDomain\",\n      \"@context\": {\n        \"domain\": {\n          \"@id\": \"schema:domainIncludes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"request_destination\": {\n          \"@id\": \"convex:requestDestination\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"DeployKey\": {\n\
  \      \"@id\": \"convex:DeployKey\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"deployment_name\": {\n          \"@id\": \"convex:deployment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ScheduledFunction\": {\n      \"@id\": \"convex:ScheduledFunction\",\n      \"@context\": {\n        \"function_path\": {\n          \"@id\": \"convex:functionPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"args\": {\n          \"@id\": \"convex:arguments\"\n        },\n        \"scheduled_time\": {\n          \"@id\": \"convex:scheduledTime\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"state\": {\n          \"@id\": \"convex:executionState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"convex:Team\",\n      \"@context\": {\n       \
  \ \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TeamMember\": {\n      \"@id\": \"convex:TeamMember\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"convex:memberRole\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/convex/refs/heads/main/json-ld/convex-context.jsonld
tags:
- Backend
- Database
- Functions
- Real-Time
- Reactive
- Serverless
- TypeScript
- JSON-LD
- Linked Data
- Semantic Web
---
