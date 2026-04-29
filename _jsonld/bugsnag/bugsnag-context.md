---
api_specs:
- filename: bugsnag-data-access-openapi.yml
  format: yaml
  label: Bugsnag Data Access API
  slug: data-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-data-access-openapi.yml
- filename: bugsnag-error-reporting-openapi.yml
  format: yaml
  label: Bugsnag Error Reporting API
  slug: error-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-error-reporting-openapi.yml
- filename: bugsnag-session-tracking-openapi.yml
  format: yaml
  label: Bugsnag Session Tracking API
  slug: session-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-session-tracking-openapi.yml
- filename: bugsnag-build-openapi.yml
  format: yaml
  label: Bugsnag Build API
  slug: build-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-build-openapi.yml
- filename: bugsnag-trace-openapi.yml
  format: yaml
  label: Bugsnag Trace API
  slug: trace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-trace-openapi.yml
class_count: 0
classes: []
context_file: json-ld/bugsnag-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/json-ld/bugsnag-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bugsnag from bugsnag.
layout: jsonld
name: Bugsnag Context
namespaces:
- prefix: bugsnag
  uri: https://bugsnag.com/vocab/
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
  name: Project
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Collaborator
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: Session
  type: ''
property_count: 7
provider_name: bugsnag
provider_slug: bugsnag
slug: bugsnag-context
source_filename: bugsnag-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bugsnag\": \"https://bugsnag.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"bugsnag:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slug\": \"bugsnag:slug\",\n        \"billingEmail\": \"schema:email\",\n        \"creator\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"autoUpgrade\": \"bugsnag:autoUpgrade\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"bugsnag:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"\
  slug\": \"bugsnag:slug\",\n        \"apiKey\": \"bugsnag:apiKey\",\n        \"type\": \"bugsnag:projectType\",\n        \"language\": \"schema:programmingLanguage\",\n        \"releaseStages\": {\n          \"@id\": \"bugsnag:releaseStages\",\n          \"@container\": \"@set\"\n        },\n        \"organization\": {\n          \"@id\": \"bugsnag:organization\",\n          \"@type\": \"@id\"\n        },\n        \"htmlUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"openErrorCount\": \"bugsnag:openErrorCount\",\n        \"collaboratorsCount\": \"bugsnag:collaboratorsCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Error\": {\n      \"@id\": \"bugsnag:Error\",\n      \"@context\": {\n        \"errorClass\": \"bugsnag:errorClass\"\
  ,\n        \"message\": \"schema:description\",\n        \"context\": \"bugsnag:context\",\n        \"severity\": \"bugsnag:severity\",\n        \"status\": \"bugsnag:status\",\n        \"events\": \"bugsnag:eventCount\",\n        \"users\": \"bugsnag:userCount\",\n        \"firstSeen\": {\n          \"@id\": \"bugsnag:firstSeen\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSeen\": {\n          \"@id\": \"bugsnag:lastSeen\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"releaseStages\": {\n          \"@id\": \"bugsnag:releaseStages\",\n          \"@container\": \"@set\"\n        },\n        \"htmlUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"project\": {\n          \"@id\": \"bugsnag:project\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"bugsnag:Event\",\n      \"@context\": {\n        \"errorClass\": \"bugsnag:errorClass\",\n        \"message\"\
  : \"schema:description\",\n        \"context\": \"bugsnag:context\",\n        \"severity\": \"bugsnag:severity\",\n        \"unhandled\": \"bugsnag:unhandled\",\n        \"exceptions\": {\n          \"@id\": \"bugsnag:exceptions\",\n          \"@container\": \"@set\"\n        },\n        \"breadcrumbs\": {\n          \"@id\": \"bugsnag:breadcrumbs\",\n          \"@container\": \"@list\"\n        },\n        \"user\": {\n          \"@id\": \"bugsnag:user\",\n          \"@type\": \"@id\"\n        },\n        \"app\": \"bugsnag:app\",\n        \"device\": \"bugsnag:device\",\n        \"receivedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"htmlUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Collaborator\": {\n      \"@id\": \"bugsnag:Collaborator\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"isAdmin\"\
  : \"bugsnag:isAdmin\",\n        \"twoFactorEnabled\": \"bugsnag:twoFactorEnabled\",\n        \"gravatarUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"bugsnag:Release\",\n      \"@context\": {\n        \"version\": \"schema:softwareVersion\",\n        \"releaseStage\": \"bugsnag:releaseStage\",\n        \"builderName\": \"bugsnag:builderName\",\n        \"sourceControl\": \"bugsnag:sourceControl\",\n        \"buildTime\": {\n          \"@id\": \"bugsnag:buildTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"errorsIntroducedCount\": \"bugsnag:errorsIntroducedCount\",\n        \"errorsSeenCount\": \"bugsnag:errorsSeenCount\",\n        \"sessionsCount\": \"bugsnag:sessionsCount\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n         \
  \ \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"bugsnag:Session\",\n      \"@context\": {\n        \"startedAt\": {\n          \"@id\": \"bugsnag:startedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"user\": {\n          \"@id\": \"bugsnag:user\",\n          \"@type\": \"@id\"\n        },\n        \"handledCount\": \"bugsnag:handledCount\",\n        \"unhandledCount\": \"bugsnag:unhandledCount\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/json-ld/bugsnag-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
