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
context_file: json-ld/dynatrace-metrics-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-metrics-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Metrics V2 from Dynatrace.
layout: jsonld
name: Dynatrace Metrics V2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: MetricDescriptor
  type: ''
- container: ''
  name: MetricDimensionDefinition
  type: ''
- container: ''
  name: MetricDefaultAggregation
  type: ''
- container: ''
  name: MetricDescriptorCollection
  type: ''
- container: ''
  name: MetricData
  type: ''
- container: ''
  name: MetricSeriesCollection
  type: ''
- container: ''
  name: MetricSeries
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
property_count: 10
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-metrics-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"MetricDescriptor\": {\n      \"@id\": \"ns:MetricDescriptor\",\n      \"@context\": {\n        \"metricId\": {\n          \"@id\": \"ns:metricId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"ns:displayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"unit\": {\n          \"@id\": \"ns:unit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dduBillable\": {\n          \"@id\": \"ns:dduBillable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"ns:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastWritten\": {\n          \"@id\": \"ns:lastWritten\",\n         \
  \ \"@type\": \"xsd:integer\"\n        },\n        \"entityType\": \"ns:entityType\",\n        \"aggregationTypes\": \"ns:aggregationTypes\",\n        \"dimensionDefinitions\": \"ns:dimensionDefinitions\",\n        \"transformations\": \"ns:transformations\",\n        \"defaultAggregation\": {\n          \"@id\": \"ns:defaultAggregation\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"MetricDimensionDefinition\": {\n      \"@id\": \"ns:MetricDimensionDefinition\",\n      \"@context\": {\n        \"key\": {\n          \"@id\": \"ns:key\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"ns:displayName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"MetricDefaultAggregation\": {\n    \
  \  \"@id\": \"ns:MetricDefaultAggregation\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameter\": {\n          \"@id\": \"ns:parameter\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n    \"MetricDescriptorCollection\": {\n      \"@id\": \"ns:MetricDescriptorCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"resolution\": {\n          \"@id\": \"ns:resolution\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metrics\": \"ns:metrics\"\n      }\n    },\n    \"MetricData\": {\n      \"@id\": \"ns:MetricData\",\n      \"@context\": {\n        \"resolution\": {\n          \"@id\": \"ns:resolution\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"result\": \"ns:result\"\n      }\n    },\n    \"MetricSeriesCollection\": {\n      \"@id\": \"ns:MetricSeriesCollection\",\n      \"@context\": {\n        \"metricId\": {\n          \"@id\": \"ns:metricId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": \"ns:data\"\n      }\n    },\n    \"MetricSeries\": {\n      \"@id\": \"ns:MetricSeries\",\n      \"@context\": {\n        \"dimensionMap\": \"ns:dimensionMap\",\n        \"dimensions\": \"ns:dimensions\",\n        \"timestamps\": \"ns:timestamps\",\n        \"values\": \"ns:values\"\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"\
  xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"constraintViolations\": \"ns:constraintViolations\"\n      }\n    },\n    \"ConstraintViolation\": {\n      \"@id\": \"ns:ConstraintViolation\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameterLocation\": {\n          \"@id\": \"ns:parameterLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-metrics-v2-context.jsonld
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
