---
api_specs:
- filename: united-technologies-arinc-messaging-openapi.yml
  format: yaml
  label: Collins Aerospace ARINC Messaging API
  slug: arinc-messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/openapi/united-technologies-arinc-messaging-openapi.yml
class_count: 8
classes:
- CloudLayer
- FlightList
- Flight
- MessageList
- Message
- SendMessageRequest
- SendMessageResponse
- WeatherData
context_file: json-ld/united-technologies-arinc-messaging-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/json-ld/united-technologies-arinc-messaging-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United Technologies Arinc Messaging from United Technologies.
layout: jsonld
name: United Technologies Arinc Messaging Context
namespaces:
- prefix: arinc
  uri: https://collinsaerospace.com/arinc/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: coverage
  type: string
- container: ''
  name: altitude
  type: integer
- container: ''
  name: total
  type: integer
- container: set
  name: flights
  type: string
- container: ''
  name: flightId
  type: string
- container: ''
  name: airlineCode
  type: string
- container: ''
  name: flightNumber
  type: string
- container: ''
  name: registration
  type: string
- container: ''
  name: departureDate
  type: date
- container: ''
  name: origin
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: scheduledDeparture
  type: dateTime
- container: ''
  name: actualOut
  type: dateTime
- container: ''
  name: actualOff
  type: dateTime
- container: ''
  name: actualOn
  type: dateTime
- container: ''
  name: actualIn
  type: dateTime
- container: ''
  name: status
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: messageId
  type: string
- container: ''
  name: messageType
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: content
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: station
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: observationTime
  type: dateTime
- container: ''
  name: rawText
  type: string
- container: ''
  name: windDirection
  type: integer
- container: ''
  name: windSpeed
  type: integer
- container: ''
  name: visibility
  type: decimal
- container: set
  name: clouds
  type: string
property_count: 32
provider_name: United Technologies
provider_slug: united-technologies
slug: united-technologies-arinc-messaging-context
source_filename: united-technologies-arinc-messaging-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"arinc\": \"https://collinsaerospace.com/arinc/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CloudLayer\": \"arinc:CloudLayer\",\n    \"FlightList\": \"arinc:FlightList\",\n    \"Flight\": \"arinc:Flight\",\n    \"MessageList\": \"arinc:MessageList\",\n    \"Message\": \"arinc:Message\",\n    \"SendMessageRequest\": \"arinc:SendMessageRequest\",\n    \"SendMessageResponse\": \"arinc:SendMessageResponse\",\n    \"WeatherData\": \"arinc:WeatherData\",\n    \"coverage\": {\n      \"@id\": \"arinc:coverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"altitude\": {\n      \"@id\": \"arinc:altitude\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"arinc:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flights\": {\n      \"@id\": \"arinc:flights\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightId\": {\n      \"@id\": \"arinc:flightId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"airlineCode\": {\n      \"@id\": \"arinc:airlineCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flightNumber\": {\n      \"@id\": \"arinc:flightNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registration\": {\n      \"@id\": \"arinc:registration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departureDate\": {\n      \"@id\": \"arinc:departureDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"origin\": {\n      \"@id\": \"arinc:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"arinc:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledDeparture\": {\n      \"@id\": \"arinc:scheduledDeparture\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actualOut\": {\n      \"@id\": \"arinc:actualOut\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  actualOff\": {\n      \"@id\": \"arinc:actualOff\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actualOn\": {\n      \"@id\": \"arinc:actualOn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actualIn\": {\n      \"@id\": \"arinc:actualIn\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"arinc:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"arinc:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageId\": {\n      \"@id\": \"arinc:messageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageType\": {\n      \"@id\": \"arinc:messageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"arinc:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"content\": {\n      \"@id\": \"arinc:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"arinc:direction\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"arinc:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"station\": {\n      \"@id\": \"arinc:station\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"arinc:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"observationTime\": {\n      \"@id\": \"arinc:observationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"rawText\": {\n      \"@id\": \"arinc:rawText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"windDirection\": {\n      \"@id\": \"arinc:windDirection\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"windSpeed\": {\n      \"@id\": \"arinc:windSpeed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"visibility\": {\n      \"@id\": \"arinc:visibility\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"clouds\": {\n      \"@id\": \"arinc:clouds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-technologies/refs/heads/main/json-ld/united-technologies-arinc-messaging-context.jsonld
tags:
- Aerospace
- Defense
- Aviation
- Manufacturing
- Connectivity
- JSON-LD
- Linked Data
- Semantic Web
---
