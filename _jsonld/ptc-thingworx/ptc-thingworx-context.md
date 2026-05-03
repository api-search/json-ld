---
api_specs:
- filename: ptc-thingworx-rest-openapi.yml
  format: yaml
  label: PTC ThingWorx REST API
  slug: thingworx-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/openapi/ptc-thingworx-rest-openapi.yml
- filename: ptc-thingworx-websocket-asyncapi.yml
  format: yaml
  label: PTC ThingWorx WebSocket/AlwaysOn API
  slug: thingworx-websocket-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/asyncapi/ptc-thingworx-websocket-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/ptc-thingworx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/json-ld/ptc-thingworx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ptc Thingworx from ptc-thingworx.
layout: jsonld
name: Ptc Thingworx Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: tw
  uri: https://docs.ptc.com/vocab/thingworx#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Thing
  type: reference
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: thingTemplate
  type: ''
- container: ''
  name: thingShape
  type: ''
- container: ''
  name: identifier
  type: ''
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: tags
  type: ''
- container: ''
  name: projectName
  type: ''
- container: ''
  name: lastModifiedDate
  type: long
- container: ''
  name: PropertyValue
  type: reference
- container: ''
  name: thingName
  type: ''
- container: ''
  name: propertyName
  type: ''
- container: ''
  name: value
  type: ''
- container: ''
  name: timestamp
  type: long
- container: ''
  name: quality
  type: ''
- container: ''
  name: EventFired
  type: reference
- container: ''
  name: eventName
  type: ''
- container: ''
  name: eventData
  type: ''
- container: ''
  name: Alert
  type: reference
- container: ''
  name: alertName
  type: ''
- container: ''
  name: alertType
  type: ''
- container: ''
  name: isAcknowledged
  type: boolean
- container: ''
  name: isCleared
  type: boolean
- container: ''
  name: DataShape
  type: reference
- container: ''
  name: fieldDefinitions
  type: ''
- container: ''
  name: baseType
  type: ''
property_count: 27
provider_name: ptc-thingworx
provider_slug: ptc-thingworx
slug: ptc-thingworx-context
source_filename: ptc-thingworx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"tw\": \"https://docs.ptc.com/vocab/thingworx#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Thing\": {\n      \"@id\": \"ssn:System\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"thingTemplate\": {\n      \"@id\": \"tw:thingTemplate\"\n    },\n    \"thingShape\": {\n      \"@id\": \"tw:thingShape\"\n    },\n    \"identifier\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\"\n    },\n    \"projectName\": {\n      \"@id\": \"schema:isPartOf\"\n    },\n    \"lastModifiedDate\": {\n      \"@id\": \"\
  schema:dateModified\",\n      \"@type\": \"xsd:long\"\n    },\n\n    \"PropertyValue\": {\n      \"@id\": \"sosa:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"thingName\": {\n      \"@id\": \"sosa:featureOfInterest\"\n    },\n    \"propertyName\": {\n      \"@id\": \"sosa:observedProperty\"\n    },\n    \"value\": {\n      \"@id\": \"sosa:hasSimpleResult\"\n    },\n    \"timestamp\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:long\"\n    },\n    \"quality\": {\n      \"@id\": \"tw:dataQuality\"\n    },\n\n    \"EventFired\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"eventName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"eventData\": {\n      \"@id\": \"schema:additionalProperty\"\n    },\n\n    \"Alert\": {\n      \"@id\": \"schema:AlarmAction\",\n      \"@type\": \"@id\"\n    },\n    \"alertName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"alertType\": {\n      \"@id\": \"tw:alertType\"\n    },\n    \"isAcknowledged\"\
  : {\n      \"@id\": \"tw:isAcknowledged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isCleared\": {\n      \"@id\": \"tw:isCleared\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"DataShape\": {\n      \"@id\": \"schema:PropertyValue\",\n      \"@type\": \"@id\"\n    },\n    \"fieldDefinitions\": {\n      \"@id\": \"tw:fieldDefinitions\"\n    },\n    \"baseType\": {\n      \"@id\": \"tw:baseType\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ptc-thingworx/refs/heads/main/json-ld/ptc-thingworx-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
