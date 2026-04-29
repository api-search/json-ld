---
class_count: 6
classes:
- Anomaly
- TimeSeries
- DetectionJob
- DataPoint
- name
- description
context_file: json-ld/anomaly-detection-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-ld/anomaly-detection-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Anomaly Detection from Anomaly Detection.
layout: jsonld
name: Anomaly Detection Context
namespaces:
- prefix: anom
  uri: https://api-evangelist.github.io/anomaly-detection/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: metricName
  type: string
- container: ''
  name: value
  type: decimal
- container: ''
  name: expectedValue
  type: decimal
- container: ''
  name: anomalyScore
  type: decimal
- container: ''
  name: severity
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: algorithm
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: seriesId
  type: string
- container: ''
  name: dimensions
  type: reference
- container: set
  name: relatedAnomalies
  type: string
- container: ''
  name: metric
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: granularity
  type: string
- container: ''
  name: seasonality
  type: string
- container: set
  name: dataPoints
  type: reference
- container: ''
  name: mode
  type: string
- container: ''
  name: sensitivity
  type: decimal
- container: set
  name: seriesIds
  type: string
property_count: 23
provider_name: Anomaly Detection
provider_slug: anomaly-detection
slug: anomaly-detection-context
source_filename: anomaly-detection-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"anom\": \"https://api-evangelist.github.io/anomaly-detection/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Anomaly\": \"anom:Anomaly\",\n    \"TimeSeries\": \"anom:TimeSeries\",\n    \"DetectionJob\": \"anom:DetectionJob\",\n    \"DataPoint\": \"anom:DataPoint\",\n\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"timestamp\": {\n      \"@id\": \"anom:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"metricName\": {\n      \"@id\": \"anom:metric_name\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"anom:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expectedValue\": {\n      \"@id\": \"anom:expected_value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"anomalyScore\": {\n      \"@id\": \"anom:anomaly_score\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"severity\": {\n      \"@id\": \"anom:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"anom:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"algorithm\": {\n      \"@id\": \"anom:algorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"anom:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesId\": {\n      \"@id\": \"anom:series_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"anom:dimensions\",\n      \"@type\": \"@id\"\n    },\n    \"relatedAnomalies\": {\n      \"@id\": \"anom:related_anomalies\",\n\
  \      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"anom:metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"anom:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"granularity\": {\n      \"@id\": \"anom:granularity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seasonality\": {\n      \"@id\": \"anom:seasonality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataPoints\": {\n      \"@id\": \"anom:data_points\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"mode\": {\n      \"@id\": \"anom:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sensitivity\": {\n      \"@id\": \"anom:sensitivity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"seriesIds\": {\n      \"@id\": \"anom:series_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-ld/anomaly-detection-context.jsonld
tags:
- Anomaly Detection
- Artificial Intelligence
- Data Science
- Fraud Detection
- Machine Learning
- Monitoring
- Observability
- Outlier Detection
- Pattern Recognition
- Security
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
