---
class_count: 0
classes: []
context_file: json-ld/baker-hughes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/baker-hughes/refs/heads/main/json-ld/baker-hughes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Baker Hughes from Baker Hughes.
layout: jsonld
name: Baker Hughes Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: baker-hughes
  uri: https://www.bakerhughes.com/vocab/
properties:
- container: ''
  name: Asset
  type: reference
- container: ''
  name: assetId
  type: string
- container: ''
  name: assetName
  type: string
- container: ''
  name: assetType
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: healthScore
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: SensorReading
  type: reference
- container: ''
  name: sensorId
  type: string
- container: ''
  name: value
  type: decimal
- container: ''
  name: unit
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: Alert
  type: reference
- container: ''
  name: alertId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: Prediction
  type: reference
- container: ''
  name: predictionId
  type: string
- container: ''
  name: failureProbability
  type: decimal
- container: ''
  name: recommendedAction
  type: string
- container: ''
  name: estimatedTimeToFailure
  type: string
- container: ''
  name: EmissionMeasurement
  type: reference
- container: ''
  name: emissionType
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: facilityId
  type: string
property_count: 25
provider_name: Baker Hughes
provider_slug: baker-hughes
slug: baker-hughes-context
tags:
- Energy Technology
- Industrial IoT
- Oil And Gas
- Asset Performance Management
- Digital Energy
- JSON-LD
- Linked Data
- Semantic Web
---
