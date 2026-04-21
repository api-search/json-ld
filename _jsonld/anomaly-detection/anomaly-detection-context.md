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
