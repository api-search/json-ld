---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Rollbar REST API
  slug: rollbar-rest-api
  spec_type: OpenAPI
  url: https://explorer.docs.rollbar.com/
- filename: rollbar-deployment-api-openapi.yml
  format: yaml
  label: Rollbar Deployment API
  slug: rollbar-deployment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-deployment-api-openapi.yml
- filename: rollbar-metrics-api-openapi.yml
  format: yaml
  label: Rollbar Metrics API
  slug: rollbar-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-metrics-api-openapi.yml
- filename: rollbar-rql-api-openapi.yml
  format: yaml
  label: Rollbar RQL API
  slug: rollbar-rql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/openapi/rollbar-rql-api-openapi.yml
- filename: rollbar-webhooks-asyncapi.yml
  format: yaml
  label: Rollbar Webhooks
  slug: rollbar-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/asyncapi/rollbar-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/rollbar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/json-ld/rollbar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rollbar from Rollbar.
layout: jsonld
name: Rollbar Context
namespaces:
- prefix: rollbar
  uri: https://api.rollbar.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Item
  type: ''
- container: ''
  name: Occurrence
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Deploy
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: AccessToken
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 8
provider_name: Rollbar
provider_slug: rollbar
slug: rollbar-context
source_filename: rollbar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rollbar\": \"https://api.rollbar.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Item\": {\n      \"@id\": \"rollbar:Item\",\n      \"@context\": {\n        \"id\": \"rollbar:itemId\",\n        \"counter\": \"rollbar:projectCounter\",\n        \"environment\": \"rollbar:environment\",\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"level\": \"rollbar:severityLevel\",\n        \"status\": \"rollbar:workflowStatus\",\n        \"hash\": \"rollbar:fingerprint\",\n        \"totalOccurrences\": {\n          \"@id\": \"rollbar:totalOccurrences\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uniqueOccurrences\": {\n          \"@id\": \"rollbar:uniqueOccurrences\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"firstOccurrenceTimestamp\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastOccurrenceTimestamp\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolvedInVersion\": \"rollbar:resolvedInVersion\",\n        \"assignedUser\": {\n          \"@id\": \"rollbar:assignedUser\",\n          \"@type\": \"@id\"\n        },\n        \"project\": {\n          \"@id\": \"rollbar:project\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Occurrence\": {\n      \"@id\": \"rollbar:Occurrence\",\n      \"@context\": {\n        \"id\": \"rollbar:occurrenceId\",\n        \"item\": {\n          \"@id\": \"rollbar:item\",\n          \"@type\": \"@id\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"environment\": \"rollbar:environment\",\n        \"codeVersion\": \"rollbar:codeVersion\",\n        \"platform\"\
  : \"rollbar:platform\",\n        \"language\": {\n          \"@id\": \"schema:programmingLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"framework\": \"rollbar:framework\",\n        \"person\": {\n          \"@id\": \"rollbar:person\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"rollbar:Project\",\n      \"@context\": {\n        \"id\": \"rollbar:projectId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": \"rollbar:projectStatus\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dateModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"account\": {\n          \"@id\": \"rollbar:account\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Deploy\": {\n      \"@id\": \"\
  rollbar:Deploy\",\n      \"@context\": {\n        \"id\": \"rollbar:deployId\",\n        \"environment\": \"rollbar:environment\",\n        \"revision\": \"rollbar:revision\",\n        \"status\": \"rollbar:deployStatus\",\n        \"comment\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"localUsername\": \"rollbar:localUsername\",\n        \"rollbarUsername\": \"rollbar:rollbarUsername\",\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"finishTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"project\": {\n          \"@id\": \"rollbar:project\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"rollbar:Team\",\n      \"@context\": {\n        \"id\": \"rollbar:teamId\",\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"accessLevel\": \"rollbar:accessLevel\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"projects\": {\n          \"@id\": \"rollbar:projects\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"rollbar:User\",\n      \"@context\": {\n        \"id\": \"rollbar:userId\",\n        \"username\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccessToken\": {\n      \"@id\": \"rollbar:AccessToken\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scopes\": {\n          \"@id\": \"rollbar:scopes\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"status\": \"rollbar:tokenStatus\",\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"rollbar:WebhookEvent\",\n      \"@context\": {\n        \"eventName\": \"rollbar:eventName\",\n        \"data\": \"rollbar:eventData\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/json-ld/rollbar-context.jsonld
tags:
- Error Tracking
- Monitoring
- Debugging
- DevOps
- Application Performance
- JSON-LD
- Linked Data
- Semantic Web
---
