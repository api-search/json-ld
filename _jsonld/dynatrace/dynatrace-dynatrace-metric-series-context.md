---
class_count: 1
classes:
- Dynatrace Metric Series
context_file: json-ld/dynatrace-dynatrace-metric-series-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-dynatrace-metric-series-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Dynatrace Metric Series from Dynatrace.
layout: jsonld
name: Dynatrace Dynatrace Metric Series Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: metricId
  type: string
- container: set
  name: data
  type: ''
property_count: 2
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-dynatrace-metric-series-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Dynatrace Metric Series\": \"dt:Dynatrace Metric Series\",\n    \"metricId\": {\n      \"@id\": \"dt:metricId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"dt:data\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-dynatrace-metric-series-context.jsonld
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
