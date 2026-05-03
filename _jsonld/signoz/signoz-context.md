---
api_specs:
- filename: signoz-openapi.yml
  format: yaml
  label: SigNoz
  slug: signoz
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/openapi/signoz-openapi.yml
class_count: 35
classes:
- Alert
- Dashboard
- Widget
- IngestionKey
- ServiceAccount
- NotificationChannel
- DowntimeSchedule
- InfraHost
- MetricRule
- id
- name
- description
- title
- createdBy
- severity
- alertType
- condition
- evalWindow
- frequency
- state
- channels
- labels
- annotations
- widgets
- panelType
- query
- isPublic
- tags
- orgId
- limits
- signalTypes
- metricName
- traceId
- spanId
- serviceName
context_file: json-ld/signoz-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/json-ld/signoz-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Signoz from SigNoz.
layout: jsonld
name: Signoz Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: signoz
  uri: https://signoz.io/vocab/
- prefix: otel
  uri: https://opentelemetry.io/docs/concepts/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
property_count: 3
provider_name: SigNoz
provider_slug: signoz
slug: signoz-context
source_filename: signoz-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"signoz\": \"https://signoz.io/vocab/\",\n    \"otel\": \"https://opentelemetry.io/docs/concepts/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Alert\": \"signoz:Alert\",\n    \"Dashboard\": \"signoz:Dashboard\",\n    \"Widget\": \"signoz:Widget\",\n    \"IngestionKey\": \"signoz:IngestionKey\",\n    \"ServiceAccount\": \"signoz:ServiceAccount\",\n    \"NotificationChannel\": \"signoz:NotificationChannel\",\n    \"DowntimeSchedule\": \"signoz:DowntimeSchedule\",\n    \"InfraHost\": \"signoz:InfraHost\",\n    \"MetricRule\": \"signoz:MetricRule\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"title\": \"schema:name\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"\
  xsd:dateTime\"\n    },\n    \"createdBy\": \"schema:author\",\n\n    \"severity\": \"signoz:severity\",\n    \"alertType\": \"signoz:alertType\",\n    \"condition\": \"signoz:condition\",\n    \"evalWindow\": \"signoz:evaluationWindow\",\n    \"frequency\": \"signoz:evaluationFrequency\",\n    \"state\": \"signoz:alertState\",\n    \"channels\": \"signoz:notificationChannels\",\n    \"labels\": \"signoz:labels\",\n    \"annotations\": \"signoz:annotations\",\n\n    \"widgets\": \"signoz:widgets\",\n    \"panelType\": \"signoz:panelType\",\n    \"query\": \"signoz:query\",\n    \"isPublic\": \"signoz:isPublic\",\n    \"tags\": \"schema:keywords\",\n\n    \"orgId\": \"signoz:organizationId\",\n    \"limits\": \"signoz:ingestionLimits\",\n    \"signalTypes\": \"otel:SignalType\",\n\n    \"metricName\": \"otel:metricName\",\n    \"traceId\": \"otel:traceId\",\n    \"spanId\": \"otel:spanId\",\n    \"serviceName\": \"schema:name\",\n    \"timestamp\": {\n      \"@id\": \"schema:DateTime\",\n\
  \      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/signoz/refs/heads/main/json-ld/signoz-context.jsonld
tags:
- APM
- Alerting
- Cloud Monitoring
- Dashboards
- Distributed Tracing
- Infrastructure Monitoring
- Logs
- Metrics
- Observability
- OpenTelemetry
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
