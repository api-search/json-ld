---
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/ciena-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/json-ld/ciena-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ciena from Ciena.
layout: jsonld
name: Ciena Context
namespaces:
- prefix: ciena
  uri: https://api.blueplanet.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: tmf
  uri: https://www.tmforum.org/resources/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: NetworkService
  type: schema:Service
- container: ''
  name: Node
  type: schema:Thing
- container: ''
  name: Link
  type: ''
- container: ''
  name: Alarm
  type: schema:Event
- container: ''
  name: ServiceEndpoint
  type: schema:EntryPoint
- container: ''
  name: serviceType
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: adminState
  type: ''
- container: ''
  name: bandwidth
  type: ''
- container: ''
  name: protectionType
  type: ''
- container: set
  name: endpoints
  type: ''
- container: ''
  name: nodeId
  type: ''
- container: ''
  name: portId
  type: ''
- container: ''
  name: direction
  type: ''
- container: ''
  name: vlanId
  type: integer
- container: ''
  name: severity
  type: ''
- container: ''
  name: raisedAt
  type: dateTime
- container: ''
  name: clearedAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: ipAddress
  type: ''
- container: ''
  name: location
  type: schema:Place
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
property_count: 24
provider_name: Ciena
provider_slug: ciena
slug: ciena-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ciena\": \"https://api.blueplanet.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"tmf\": \"https://www.tmforum.org/resources/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"NetworkService\": {\n      \"@id\": \"ciena:NetworkService\",\n      \"@type\": \"schema:Service\"\n    },\n    \"Node\": {\n      \"@id\": \"ciena:NetworkNode\",\n      \"@type\": \"schema:Thing\"\n    },\n    \"Link\": {\n      \"@id\": \"ciena:NetworkLink\"\n    },\n    \"Alarm\": {\n      \"@id\": \"ciena:NetworkAlarm\",\n      \"@type\": \"schema:Event\"\n    },\n    \"ServiceEndpoint\": {\n      \"@id\": \"ciena:ServiceEndpoint\",\n      \"@type\": \"schema:EntryPoint\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"serviceType\": {\n      \"@id\": \"ciena:serviceType\"\n    },\n    \"state\"\
  : {\n      \"@id\": \"ciena:operationalState\"\n    },\n    \"adminState\": {\n      \"@id\": \"ciena:administrativeState\"\n    },\n    \"bandwidth\": {\n      \"@id\": \"schema:amount\"\n    },\n    \"protectionType\": {\n      \"@id\": \"ciena:protectionScheme\"\n    },\n    \"endpoints\": {\n      \"@id\": \"ciena:hasEndpoint\",\n      \"@container\": \"@set\"\n    },\n    \"nodeId\": {\n      \"@id\": \"ciena:nodeReference\"\n    },\n    \"portId\": {\n      \"@id\": \"ciena:portReference\"\n    },\n    \"direction\": {\n      \"@id\": \"ciena:endpointDirection\"\n    },\n    \"vlanId\": {\n      \"@id\": \"ciena:vlanIdentifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"ciena:alarmSeverity\"\n    },\n    \"raisedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clearedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"schema:ipAddressV4\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"schema:Place\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/json-ld/ciena-context.jsonld
tags:
- MEF
- NETCONF
- Network Automation
- Network Management
- Optical
- RESTCONF
- SDN
- Telecom
- TM Forum
- JSON-LD
- Linked Data
- Semantic Web
---
