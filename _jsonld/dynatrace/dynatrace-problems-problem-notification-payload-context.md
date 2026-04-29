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
class_count: 1
classes:
- ProblemNotificationPayload
context_file: json-ld/dynatrace-problems-problem-notification-payload-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-problem-notification-payload-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Problems Problem Notification Payload from Dynatrace.
layout: jsonld
name: Dynatrace Problems Problem Notification Payload Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ProblemID
  type: string
- container: ''
  name: ProblemTitle
  type: string
- container: ''
  name: ProblemURL
  type: string
- container: ''
  name: ProblemSeverity
  type: string
- container: ''
  name: ProblemStatus
  type: string
- container: set
  name: ImpactedEntities
  type: ''
- container: ''
  name: ImpactedEntityNames
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: ProblemDetailsJSON
  type: string
property_count: 10
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-problems-problem-notification-payload-context
source_filename: dynatrace-problems-problem-notification-payload-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProblemNotificationPayload\": \"dt:ProblemNotificationPayload\",\n    \"ProblemID\": {\n      \"@id\": \"dt:ProblemID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProblemTitle\": {\n      \"@id\": \"dt:ProblemTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProblemURL\": {\n      \"@id\": \"dt:ProblemURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProblemSeverity\": {\n      \"@id\": \"dt:ProblemSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProblemStatus\": {\n      \"@id\": \"dt:ProblemStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpactedEntities\": {\n      \"@id\": \"dt:ImpactedEntities\",\n      \"@container\": \"@set\"\n    },\n    \"ImpactedEntityNames\": {\n      \"@id\": \"dt:ImpactedEntityNames\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Tags\": {\n      \"@id\": \"dt:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"dt:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProblemDetailsJSON\": {\n      \"@id\": \"dt:ProblemDetailsJSON\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-problem-notification-payload-context.jsonld
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
