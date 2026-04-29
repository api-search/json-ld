---
class_count: 8
classes:
- ConstraintViolation
- MetricData
- MetricDefaultAggregation
- MetricDescriptorCollection
- MetricDescriptor
- MetricDimensionDefinition
- MetricSeriesCollection
- MetricSeries
context_file: json-ld/dynatrace-metrics-api-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-metrics-api-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Metrics Api V2 from Dynatrace.
layout: jsonld
name: Dynatrace Metrics Api V2 Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: path
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: parameterLocation
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: nextPageKey
  type: string
- container: ''
  name: totalCount
  type: integer
- container: set
  name: result
  type: ''
- container: ''
  name: type
  type: string
- container: ''
  name: parameter
  type: decimal
- container: set
  name: metrics
  type: ''
- container: ''
  name: metricId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: dduBillable
  type: boolean
- container: ''
  name: created
  type: integer
- container: ''
  name: lastWritten
  type: integer
- container: set
  name: entityType
  type: ''
- container: set
  name: aggregationTypes
  type: ''
- container: set
  name: dimensionDefinitions
  type: ''
- container: set
  name: transformations
  type: ''
- container: ''
  name: defaultAggregation
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: name
  type: string
- container: set
  name: data
  type: ''
- container: ''
  name: dimensionMap
  type: ''
- container: set
  name: dimensions
  type: ''
- container: set
  name: timestamps
  type: ''
- container: set
  name: values
  type: ''
property_count: 30
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-metrics-api-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConstraintViolation\": \"dt:ConstraintViolation\",\n    \"path\": {\n      \"@id\": \"dt:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"dt:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterLocation\": {\n      \"@id\": \"dt:parameterLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"dt:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricData\": \"dt:MetricData\",\n    \"resolution\": {\n      \"@id\": \"dt:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextPageKey\": {\n      \"@id\": \"dt:nextPageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"dt:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"result\"\
  : {\n      \"@id\": \"dt:result\",\n      \"@container\": \"@set\"\n    },\n    \"MetricDefaultAggregation\": \"dt:MetricDefaultAggregation\",\n    \"type\": {\n      \"@id\": \"dt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameter\": {\n      \"@id\": \"dt:parameter\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MetricDescriptorCollection\": \"dt:MetricDescriptorCollection\",\n    \"metrics\": {\n      \"@id\": \"dt:metrics\",\n      \"@container\": \"@set\"\n    },\n    \"MetricDescriptor\": \"dt:MetricDescriptor\",\n    \"metricId\": {\n      \"@id\": \"dt:metricId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"dt:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"dt:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dduBillable\": {\n      \"@id\": \"dt:dduBillable\",\n      \"\
  @type\": \"xsd:boolean\"\n    },\n    \"created\": {\n      \"@id\": \"dt:created\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastWritten\": {\n      \"@id\": \"dt:lastWritten\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityType\": {\n      \"@id\": \"dt:entityType\",\n      \"@container\": \"@set\"\n    },\n    \"aggregationTypes\": {\n      \"@id\": \"dt:aggregationTypes\",\n      \"@container\": \"@set\"\n    },\n    \"dimensionDefinitions\": {\n      \"@id\": \"dt:dimensionDefinitions\",\n      \"@container\": \"@set\"\n    },\n    \"transformations\": {\n      \"@id\": \"dt:transformations\",\n      \"@container\": \"@set\"\n    },\n    \"defaultAggregation\": {\n      \"@id\": \"dt:defaultAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricDimensionDefinition\": \"dt:MetricDimensionDefinition\",\n    \"key\": {\n      \"@id\": \"dt:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"MetricSeriesCollection\": \"dt:MetricSeriesCollection\",\n    \"data\": {\n      \"@id\": \"dt:data\",\n      \"@container\": \"@set\"\n    },\n    \"MetricSeries\": \"dt:MetricSeries\",\n    \"dimensionMap\": {\n      \"@id\": \"dt:dimensionMap\"\n    },\n    \"dimensions\": {\n      \"@id\": \"dt:dimensions\",\n      \"@container\": \"@set\"\n    },\n    \"timestamps\": {\n      \"@id\": \"dt:timestamps\",\n      \"@container\": \"@set\"\n    },\n    \"values\": {\n      \"@id\": \"dt:values\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-metrics-api-v2-context.jsonld
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
