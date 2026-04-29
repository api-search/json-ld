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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"baker-hughes\": \"https://www.bakerhughes.com/vocab/\",\n\n    \"Asset\": {\n      \"@id\": \"baker-hughes:Asset\",\n      \"@type\": \"@id\"\n    },\n    \"assetId\": {\n      \"@id\": \"baker-hughes:assetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetName\": {\n      \"@id\": \"baker-hughes:assetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetType\": {\n      \"@id\": \"baker-hughes:assetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"baker-hughes:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthScore\": {\n      \"@id\": \"baker-hughes:healthScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"baker-hughes:status\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"SensorReading\": {\n      \"@id\": \"baker-hughes:SensorReading\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"sensorId\": {\n      \"@id\": \"baker-hughes:sensorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"baker-hughes:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unit\": {\n      \"@id\": \"baker-hughes:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"baker-hughes:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Alert\": {\n      \"@id\": \"baker-hughes:Alert\",\n      \"@type\": \"@id\"\n    },\n    \"alertId\": {\n      \"@id\": \"baker-hughes:alertId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"baker-hughes:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"baker-hughes:message\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Prediction\": {\n      \"@id\": \"baker-hughes:Prediction\",\n      \"@type\": \"@id\"\n    },\n    \"predictionId\": {\n      \"@id\": \"\
  baker-hughes:predictionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureProbability\": {\n      \"@id\": \"baker-hughes:failureProbability\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"recommendedAction\": {\n      \"@id\": \"baker-hughes:recommendedAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedTimeToFailure\": {\n      \"@id\": \"baker-hughes:estimatedTimeToFailure\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"EmissionMeasurement\": {\n      \"@id\": \"baker-hughes:EmissionMeasurement\",\n      \"@type\": \"@id\"\n    },\n    \"emissionType\": {\n      \"@id\": \"baker-hughes:emissionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"baker-hughes:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"facilityId\": {\n      \"@id\": \"baker-hughes:facilityId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/baker-hughes/refs/heads/main/json-ld/baker-hughes-context.jsonld
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
