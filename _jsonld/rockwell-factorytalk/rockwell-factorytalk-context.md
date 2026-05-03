---
api_specs:
- filename: rockwell-factorytalk-optix-openapi.yml
  format: yaml
  label: Rockwell FactoryTalk Optix REST API
  slug: factorytalk-optix-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/openapi/rockwell-factorytalk-optix-openapi.yml
- filename: rockwell-factorytalk-realtime-asyncapi.yml
  format: yaml
  label: Rockwell FactoryTalk Hub API
  slug: factorytalk-hub-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/asyncapi/rockwell-factorytalk-realtime-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/rockwell-factorytalk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/json-ld/rockwell-factorytalk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rockwell Factorytalk from rockwell-factorytalk.
layout: jsonld
name: Rockwell Factorytalk Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: ft
  uri: https://www.rockwellautomation.com/vocab/factorytalk#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
properties:
- container: ''
  name: Tag
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: displayName
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: dataType
  type: ''
- container: ''
  name: engineeringUnit
  type: ''
- container: ''
  name: readOnly
  type: boolean
- container: ''
  name: alarmEnabled
  type: boolean
- container: ''
  name: deadband
  type: decimal
- container: ''
  name: TagValue
  type: reference
- container: ''
  name: value
  type: ''
- container: ''
  name: quality
  type: ''
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: Alarm
  type: reference
- container: ''
  name: alarmId
  type: ''
- container: ''
  name: alarmName
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: severity
  type: ''
- container: ''
  name: activationTime
  type: dateTime
- container: ''
  name: acknowledgmentTime
  type: dateTime
- container: ''
  name: acknowledgedBy
  type: ''
- container: ''
  name: TrendDataPoint
  type: reference
- container: ''
  name: Recipe
  type: reference
- container: ''
  name: parameters
  type: ''
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: modifiedBy
  type: ''
property_count: 26
provider_name: rockwell-factorytalk
provider_slug: rockwell-factorytalk
slug: rockwell-factorytalk-context
source_filename: rockwell-factorytalk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"ft\": \"https://www.rockwellautomation.com/vocab/factorytalk#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n\n    \"Tag\": {\n      \"@id\": \"sosa:ObservableProperty\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"displayName\": {\n      \"@id\": \"schema:alternateName\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dataType\": {\n      \"@id\": \"ft:dataType\"\n    },\n    \"engineeringUnit\": {\n      \"@id\": \"qudt:unit\"\n    },\n    \"readOnly\": {\n      \"@id\": \"ft:readOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"alarmEnabled\": {\n      \"@id\": \"ft:alarmEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deadband\"\
  : {\n      \"@id\": \"ft:deadband\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"TagValue\": {\n      \"@id\": \"sosa:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"sosa:hasSimpleResult\"\n    },\n    \"quality\": {\n      \"@id\": \"ft:dataQuality\"\n    },\n    \"timestamp\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Alarm\": {\n      \"@id\": \"schema:AlarmAction\",\n      \"@type\": \"@id\"\n    },\n    \"alarmId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"alarmName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"severity\": {\n      \"@id\": \"ft:alarmSeverity\"\n    },\n    \"activationTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledgmentTime\": {\n      \"@id\": \"ft:acknowledgmentTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledgedBy\"\
  : {\n      \"@id\": \"schema:agent\"\n    },\n\n    \"TrendDataPoint\": {\n      \"@id\": \"sosa:Observation\",\n      \"@type\": \"@id\"\n    },\n\n    \"Recipe\": {\n      \"@id\": \"schema:HowTo\",\n      \"@type\": \"@id\"\n    },\n    \"parameters\": {\n      \"@id\": \"schema:step\"\n    },\n    \"lastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedBy\": {\n      \"@id\": \"schema:author\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/json-ld/rockwell-factorytalk-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
