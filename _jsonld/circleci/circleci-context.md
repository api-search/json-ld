---
api_specs:
- filename: circleci-rest-api-v2-openapi.yml
  format: yaml
  label: CircleCI REST API V2
  slug: rest-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-rest-api-v2-openapi.yml
- filename: circleci-rest-api-v1-openapi.yml
  format: yaml
  label: CircleCI REST API V1
  slug: rest-api-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-rest-api-v1-openapi.yml
- filename: circleci-runner-api-openapi.yml
  format: yaml
  label: CircleCI Self-Hosted Runner API
  slug: runner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-runner-api-openapi.yml
- filename: circleci-webhooks-asyncapi.yml
  format: yaml
  label: CircleCI Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/asyncapi/circleci-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/circleci-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/json-ld/circleci-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Circleci from CircleCI.
layout: jsonld
name: Circleci Context
namespaces:
- prefix: circleci
  uri: https://circleci.com/api/v2/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Context
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: Runner
  type: ''
- container: ''
  name: Artifact
  type: ''
- container: ''
  name: WebhookSubscription
  type: ''
- container: ''
  name: Organization
  type: ''
property_count: 10
provider_name: CircleCI
provider_slug: circleci
slug: circleci-context
source_filename: circleci-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"circleci\": \"https://circleci.com/api/v2/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Pipeline\": {\n      \"@id\": \"circleci:Pipeline\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"number\": \"circleci:number\",\n        \"state\": \"circleci:state\",\n        \"projectSlug\": \"circleci:project_slug\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"trigger\": \"circleci:trigger\",\n        \"vcs\": \"circleci:vcs\"\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"circleci:Workflow\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n  \
  \      \"status\": \"circleci:status\",\n        \"pipelineId\": \"circleci:pipeline_id\",\n        \"pipelineNumber\": \"circleci:pipeline_number\",\n        \"projectSlug\": \"circleci:project_slug\",\n        \"startedBy\": \"circleci:started_by\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"stoppedAt\": {\n          \"@id\": \"circleci:stopped_at\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"circleci:Job\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n        \"number\": \"circleci:number\",\n        \"status\": \"circleci:status\",\n        \"type\": \"circleci:job_type\",\n        \"webUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"startedAt\": {\n          \"@id\": \"circleci:started_at\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"stoppedAt\": {\n          \"@id\": \"circleci:stopped_at\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": \"circleci:duration\",\n        \"executor\": \"circleci:executor\",\n        \"parallelism\": \"circleci:parallelism\",\n        \"dependencies\": {\n          \"@id\": \"circleci:dependencies\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"circleci:Project\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n        \"slug\": \"circleci:slug\",\n        \"organizationName\": \"schema:memberOf\",\n        \"organizationId\": \"circleci:organization_id\",\n        \"vcsInfo\": \"circleci:vcs_info\",\n        \"vcsUrl\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Context\": {\n      \"@id\": \"circleci:Context\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n\
  \        \"name\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"circleci:Schedule\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"timetable\": \"circleci:timetable\",\n        \"projectSlug\": \"circleci:project_slug\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Runner\": {\n      \"@id\": \"circleci:Runner\",\n      \"@context\": {\n        \"resourceClass\": \"circleci:resource_class\",\n        \"hostname\": \"circleci:hostname\",\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n\
  \        \"os\": \"schema:operatingSystem\",\n        \"firstConnected\": {\n          \"@id\": \"circleci:first_connected\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastConnected\": {\n          \"@id\": \"circleci:last_connected\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUsed\": {\n          \"@id\": \"circleci:last_used\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Artifact\": {\n      \"@id\": \"circleci:Artifact\",\n      \"@context\": {\n        \"path\": \"circleci:path\",\n        \"nodeIndex\": \"circleci:node_index\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WebhookSubscription\": {\n      \"@id\": \"circleci:WebhookSubscription\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"circleci:webhook_url\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"circleci:events\",\n          \"@container\": \"@set\"\n        },\n        \"verifyTls\": \"circleci:verify_tls\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"circleci:Organization\",\n      \"@context\": {\n        \"id\": \"circleci:id\",\n        \"name\": \"schema:name\",\n        \"slug\": \"circleci:slug\",\n        \"vcsType\": \"circleci:vcs_type\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/json-ld/circleci-context.jsonld
tags:
- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
