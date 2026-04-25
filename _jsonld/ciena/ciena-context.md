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
