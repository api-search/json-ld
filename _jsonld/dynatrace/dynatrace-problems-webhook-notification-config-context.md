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
- WebhookNotificationConfig
context_file: json-ld/dynatrace-problems-webhook-notification-config-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-webhook-notification-config-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Problems Webhook Notification Config from Dynatrace.
layout: jsonld
name: Dynatrace Problems Webhook Notification Config Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: url
  type: string
- container: ''
  name: alertingProfile
  type: string
- container: set
  name: headers
  type: ''
- container: ''
  name: acceptAnyCertificate
  type: boolean
- container: ''
  name: payload
  type: string
property_count: 8
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-problems-webhook-notification-config-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WebhookNotificationConfig\": \"dt:WebhookNotificationConfig\",\n    \"type\": {\n      \"@id\": \"dt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"dt:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertingProfile\": {\n      \"@id\": \"dt:alertingProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"dt:headers\",\n      \"@container\": \"@set\"\n    },\n    \"acceptAnyCertificate\": {\n      \"@id\": \"dt:acceptAnyCertificate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"payload\": {\n      \"@id\": \"dt:payload\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-webhook-notification-config-context.jsonld
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
