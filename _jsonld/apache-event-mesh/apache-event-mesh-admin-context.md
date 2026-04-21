---
class_count: 5
classes:
- CloudEvent
- Client
- ApiResponse
- Subscription
- url
context_file: json-ld/apache-event-mesh-admin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-event-mesh/refs/heads/main/json-ld/apache-event-mesh-admin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Event Mesh Admin from Apache EventMesh.
layout: jsonld
name: Apache Event Mesh Admin Context
namespaces:
- prefix: eventmesh
  uri: https://eventmesh.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: specversion
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: datacontenttype
  type: string
- container: ''
  name: dataschema
  type: reference
- container: ''
  name: subject
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: data
  type: string
- container: ''
  name: data_base64
  type: string
- container: ''
  name: env
  type: string
- container: ''
  name: idc
  type: string
- container: ''
  name: sys
  type: string
- container: ''
  name: ip
  type: string
- container: ''
  name: pid
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: group
  type: string
- container: set
  name: topics
  type: string
- container: ''
  name: retCode
  type: integer
- container: ''
  name: retMsg
  type: string
- container: ''
  name: topic
  type: string
property_count: 21
provider_name: Apache EventMesh
provider_slug: apache-event-mesh
slug: apache-event-mesh-admin-context
tags:
- Apache
- CloudEvents
- Event-Driven
- Messaging
- Open Source
- Pub-Sub
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
