---
api_specs:
- filename: dynatrace-metrics-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Metrics API v2
  slug: dynatrace-metrics-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-metrics-api-v2-openapi.yml
- filename: dynatrace-log-monitoring-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Log Monitoring API v2
  slug: dynatrace-log-monitoring-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-log-monitoring-api-v2-openapi.yml
- filename: dynatrace-account-management-api-openapi.yml
  format: yaml
  label: Dynatrace Account Management API
  slug: dynatrace-account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-account-management-api-openapi.yml
- filename: dynatrace-events-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Events API v2
  slug: dynatrace-events-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-events-api-v2-openapi.yml
- filename: dynatrace-problems-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Problems API v2
  slug: dynatrace-problems-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-problems-api-v2-openapi.yml
- filename: dynatrace-entities-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Entities API v2
  slug: dynatrace-entities-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-entities-api-v2-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dynatrace-problems-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Problems V2 from Dynatrace.
layout: jsonld
name: Dynatrace Problems V2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Problem
  type: ''
- container: ''
  name: ProblemCollection
  type: ''
- container: ''
  name: ProblemCloseRequest
  type: ''
- container: ''
  name: ProblemCloseResult
  type: ''
- container: ''
  name: CommentRequestBody
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: CommentCollection
  type: ''
- container: ''
  name: EntityStub
  type: ''
- container: ''
  name: ManagementZone
  type: ''
- container: ''
  name: AlertingProfileStub
  type: ''
- container: ''
  name: ErrorEnvelope
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ConstraintViolation
  type: ''
property_count: 13
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-problems-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Problem\": {\n      \"@id\": \"ns:Problem\",\n      \"@context\": {\n        \"problemId\": {\n          \"@id\": \"ns:problemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayId\": {\n          \"@id\": \"ns:displayId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severityLevel\": {\n          \"@id\": \"ns:severityLevel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"ns:startTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endTime\": {\n          \"@id\": \"ns:endTime\",\n          \"@type\": \"xsd:integer\"\n\
  \        },\n        \"affectedEntities\": \"ns:affectedEntities\",\n        \"impactedEntities\": \"ns:impactedEntities\",\n        \"rootCauseEntity\": {\n          \"@id\": \"ns:rootCauseEntity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"managementZones\": \"ns:managementZones\",\n        \"problemFilters\": \"ns:problemFilters\"\n      }\n    },\n    \"ProblemCollection\": {\n      \"@id\": \"ns:ProblemCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pageSize\": {\n          \"@id\": \"ns:pageSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"problems\": \"ns:problems\"\n      }\n    },\n    \"ProblemCloseRequest\": {\n      \"@id\": \"ns:ProblemCloseRequest\",\n      \"@context\": {\n        \"message\": {\n        \
  \  \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ProblemCloseResult\": {\n      \"@id\": \"ns:ProblemCloseResult\",\n      \"@context\": {\n        \"problemId\": {\n          \"@id\": \"ns:problemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"closing\": {\n          \"@id\": \"ns:closing\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"CommentRequestBody\": {\n      \"@id\": \"ns:CommentRequestBody\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": {\n          \"@id\": \"ns:context\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Comment\": {\n      \"@id\": \"ns:Comment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAtTimestamp\": {\n          \"@id\": \"ns:createdAtTimestamp\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"authorName\": {\n          \"@id\": \"ns:authorName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"ns:content\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": {\n          \"@id\": \"ns:context\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CommentCollection\": {\n      \"@id\": \"ns:CommentCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"comments\": \"ns:comments\"\n      }\n    },\n    \"EntityStub\": {\n      \"@id\": \"ns:EntityStub\",\n      \"@context\": {\n        \"entityId\": {\n          \"@id\": \"ns:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n\
  \          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ManagementZone\": {\n      \"@id\": \"ns:ManagementZone\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"AlertingProfileStub\": {\n      \"@id\": \"ns:AlertingProfileStub\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"xsd:string\"\
  \n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"constraintViolations\": \"ns:constraintViolations\"\n      }\n    },\n    \"ConstraintViolation\": {\n      \"@id\": \"ns:ConstraintViolation\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameterLocation\": {\n          \"@id\": \"ns:parameterLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-v2-context.jsonld
tags:
- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
