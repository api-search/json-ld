---
class_count: 7
classes:
- MonitoredEntity
- MetricDescriptor
- MetricDataPoint
- Problem
- Event
- LogRecord
- SyntheticMonitor
context_file: json-ld/dynatrace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace from Dynatrace.
layout: jsonld
name: Dynatrace Context
namespaces:
- prefix: dynatrace
  uri: https://docs.dynatrace.com/docs/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: entityId
  type: ''
- container: ''
  name: displayName
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: firstSeenTms
  type: long
- container: ''
  name: lastSeenTms
  type: long
- container: ''
  name: tags
  type: ''
- container: ''
  name: metricId
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: unit
  type: ''
- container: ''
  name: aggregationTypes
  type: ''
- container: ''
  name: timestamps
  type: ''
- container: ''
  name: values
  type: ''
- container: ''
  name: dimensionMap
  type: ''
- container: ''
  name: problemId
  type: ''
- container: ''
  name: displayId
  type: ''
- container: ''
  name: title
  type: ''
- container: ''
  name: severityLevel
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: startTime
  type: long
- container: ''
  name: endTime
  type: long
- container: ''
  name: eventId
  type: ''
- container: ''
  name: eventType
  type: ''
- container: ''
  name: content
  type: ''
- container: ''
  name: severity
  type: ''
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: name
  type: ''
- container: ''
  name: locations
  type: ''
- container: ''
  name: frequency
  type: ''
property_count: 28
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-context
source_json: "{\n  \"@context\": {\n    \"dynatrace\": \"https://docs.dynatrace.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"MonitoredEntity\": \"dynatrace:MonitoredEntity\",\n    \"MetricDescriptor\": \"dynatrace:MetricDescriptor\",\n    \"MetricDataPoint\": \"dynatrace:MetricDataPoint\",\n    \"Problem\": \"dynatrace:Problem\",\n    \"Event\": \"dynatrace:Event\",\n    \"LogRecord\": \"dynatrace:LogRecord\",\n    \"SyntheticMonitor\": \"dynatrace:SyntheticMonitor\",\n\n    \"entityId\": {\n      \"@id\": \"@id\",\n      \"@comment\": \"Maps the Dynatrace entityId field to the JSON-LD @id, making each monitored entity uniquely addressable as a linked data resource.\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:name\",\n      \"@comment\": \"The human-readable display name of the monitored entity, mapped to schema.org/name for interoperability.\"\n\
  \    },\n    \"type\": {\n      \"@id\": \"schema:additionalType\",\n      \"@comment\": \"The entity type (e.g., SERVICE, HOST) mapped to schema:additionalType to classify entities beyond the base MonitoredEntity type.\"\n    },\n    \"firstSeenTms\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:long\",\n      \"@comment\": \"The Unix timestamp in milliseconds when the entity was first observed, mapped to dcterms:created.\"\n    },\n    \"lastSeenTms\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:long\",\n      \"@comment\": \"The Unix timestamp in milliseconds when the entity was last observed, mapped to dcterms:modified.\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@comment\": \"Entity tags mapped to schema:keywords to enable semantic search and categorization.\"\n    },\n\n    \"metricId\": {\n      \"@id\": \"schema:identifier\",\n      \"@comment\": \"The metric key identifier, mapped to schema:identifier for the MetricDescriptor\
  \ context.\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\",\n      \"@comment\": \"The description of the metric, mapped to dcterms:description.\"\n    },\n    \"unit\": {\n      \"@id\": \"schema:unitCode\",\n      \"@comment\": \"The unit of measurement for the metric (e.g., Percent, Byte), mapped to schema:unitCode.\"\n    },\n    \"aggregationTypes\": {\n      \"@id\": \"schema:additionalProperty\",\n      \"@comment\": \"The supported aggregation types for the metric (e.g., avg, sum, max), mapped to schema:additionalProperty.\"\n    },\n\n    \"timestamps\": {\n      \"@id\": \"dcterms:date\",\n      \"@comment\": \"The array of Unix timestamps for metric data points, mapped to dcterms:date for the MetricDataPoint context.\"\n    },\n    \"values\": {\n      \"@id\": \"schema:value\",\n      \"@comment\": \"The array of metric values corresponding to timestamps, mapped to schema:value.\"\n    },\n    \"dimensionMap\": {\n      \"@id\": \"schema:additionalProperty\"\
  ,\n      \"@comment\": \"The dimension key-value map for a metric series, mapped to schema:additionalProperty.\"\n    },\n\n    \"problemId\": {\n      \"@id\": \"@id\",\n      \"@comment\": \"Maps the Dynatrace problemId to the JSON-LD @id, making each problem uniquely addressable.\"\n    },\n    \"displayId\": {\n      \"@id\": \"schema:identifier\",\n      \"@comment\": \"The human-readable problem identifier (e.g., P-123456), mapped to schema:identifier.\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@comment\": \"The problem title generated by Davis AI, mapped to schema:name.\"\n    },\n    \"severityLevel\": {\n      \"@id\": \"schema:additionalType\",\n      \"@comment\": \"The severity classification of the problem, mapped to schema:additionalType.\"\n    },\n    \"status\": {\n      \"@id\": \"schema:eventStatus\",\n      \"@comment\": \"The lifecycle status of the problem (OPEN or RESOLVED), mapped to schema:eventStatus.\"\n    },\n    \"startTime\": {\n\
  \      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:long\",\n      \"@comment\": \"The Unix timestamp in milliseconds when the problem started, mapped to dcterms:created.\"\n    },\n    \"endTime\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:long\",\n      \"@comment\": \"The Unix timestamp in milliseconds when the problem ended (-1 if still open), mapped to dcterms:modified.\"\n    },\n\n    \"eventId\": {\n      \"@id\": \"@id\",\n      \"@comment\": \"Maps the Dynatrace eventId to the JSON-LD @id, making each event uniquely addressable.\"\n    },\n    \"eventType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@comment\": \"The type of the Dynatrace event (e.g., CUSTOM_DEPLOYMENT, AVAILABILITY_EVENT), mapped to schema:additionalType.\"\n    },\n\n    \"content\": {\n      \"@id\": \"schema:description\",\n      \"@comment\": \"The log record message content, mapped to schema:description.\"\n    },\n    \"severity\": {\n      \"@id\": \"schema:additionalType\"\
  ,\n      \"@comment\": \"The severity level of the log record (e.g., ERROR, WARNING, INFO), mapped to schema:additionalType.\"\n    },\n    \"timestamp\": {\n      \"@id\": \"dcterms:date\",\n      \"@type\": \"xsd:dateTime\",\n      \"@comment\": \"The timestamp of the log record, mapped to dcterms:date with xsd:dateTime type.\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@comment\": \"The display name of the synthetic monitor, mapped to schema:name.\"\n    },\n    \"locations\": {\n      \"@id\": \"schema:location\",\n      \"@comment\": \"The list of locations from which the synthetic monitor executes, mapped to schema:location.\"\n    },\n    \"frequency\": {\n      \"@id\": \"schema:frequency\",\n      \"@comment\": \"The execution frequency of the synthetic monitor, mapped to schema:frequency.\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-context.jsonld
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
