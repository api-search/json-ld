---
api_specs:
- filename: osisoft-pi-web-api-openapi.yml
  format: yaml
  label: OSIsoft PI Web API
  slug: pi-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/openapi/osisoft-pi-web-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/osisoft-pi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/json-ld/osisoft-pi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Osisoft Pi from osisoft-pi.
layout: jsonld
name: Osisoft Pi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: pi
  uri: https://docs.aveva.com/bundle/pi-web-api-reference/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
properties:
- container: ''
  name: PIPoint
  type: reference
- container: ''
  name: WebId
  type: ''
- container: ''
  name: Id
  type: integer
- container: ''
  name: Name
  type: ''
- container: ''
  name: Path
  type: ''
- container: ''
  name: PointType
  type: ''
- container: ''
  name: EngineeringUnits
  type: ''
- container: ''
  name: Description
  type: ''
- container: ''
  name: TimedValue
  type: reference
- container: ''
  name: Timestamp
  type: dateTime
- container: ''
  name: Value
  type: ''
- container: ''
  name: Good
  type: boolean
- container: ''
  name: Questionable
  type: boolean
- container: ''
  name: Substituted
  type: boolean
- container: ''
  name: UnitsAbbreviation
  type: ''
- container: ''
  name: Element
  type: reference
- container: ''
  name: Attribute
  type: reference
- container: ''
  name: HasChildren
  type: boolean
- container: ''
  name: TemplateName
  type: ''
- container: ''
  name: EventFrame
  type: reference
- container: ''
  name: StartTime
  type: dateTime
- container: ''
  name: EndTime
  type: dateTime
- container: ''
  name: Severity
  type: ''
property_count: 23
provider_name: osisoft-pi
provider_slug: osisoft-pi
slug: osisoft-pi-context
source_filename: osisoft-pi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"pi\": \"https://docs.aveva.com/bundle/pi-web-api-reference/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n\n    \"PIPoint\": {\n      \"@id\": \"sosa:ObservableProperty\",\n      \"@type\": \"@id\"\n    },\n    \"WebId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"Id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"Path\": {\n      \"@id\": \"pi:path\"\n    },\n    \"PointType\": {\n      \"@id\": \"pi:pointType\"\n    },\n    \"EngineeringUnits\": {\n      \"@id\": \"qudt:unit\"\n    },\n    \"Description\": {\n      \"@id\": \"schema:description\"\n    },\n\n    \"TimedValue\": {\n      \"@id\": \"sosa:Observation\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"sosa:resultTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Value\": {\n      \"@id\": \"sosa:hasSimpleResult\"\n    },\n    \"Good\": {\n      \"@id\": \"pi:goodQuality\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Questionable\": {\n      \"@id\": \"pi:questionable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Substituted\": {\n      \"@id\": \"pi:substituted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"UnitsAbbreviation\": {\n      \"@id\": \"qudt:unit\"\n    },\n\n    \"Element\": {\n      \"@id\": \"ssn:System\",\n      \"@type\": \"@id\"\n    },\n    \"Attribute\": {\n      \"@id\": \"ssn:Property\",\n      \"@type\": \"@id\"\n    },\n    \"HasChildren\": {\n      \"@id\": \"pi:hasChildren\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"pi:templateName\"\n    },\n\n    \"EventFrame\": {\n      \"@id\": \"schema:Event\",\n      \"@type\":\
  \ \"@id\"\n    },\n    \"StartTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Severity\": {\n      \"@id\": \"pi:severity\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/json-ld/osisoft-pi-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
