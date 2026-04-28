---
class_count: 4
classes:
- CloudEvent
- Subscription
- Filter
- ProtocolSettings
context_file: json-ld/cloudevents-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudevents/refs/heads/main/json-ld/cloudevents-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudevents from CloudEvents.
layout: jsonld
name: Cloudevents Context
namespaces:
- prefix: ce
  uri: https://cloudevents.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
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
  type: ''
- container: ''
  name: data_base64
  type: base64Binary
- container: ''
  name: sink
  type: reference
- container: ''
  name: protocol
  type: string
- container: ''
  name: protocolSettings
  type: ''
- container: set
  name: filters
  type: ''
- container: set
  name: types
  type: ''
- container: ''
  name: config
  type: ''
- container: ''
  name: dialect
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: contentMode
  type: string
- container: ''
  name: traceparent
  type: string
- container: ''
  name: tracestate
  type: string
- container: ''
  name: partitionkey
  type: string
- container: ''
  name: sampledrate
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: version
  type: string
property_count: 27
provider_name: CloudEvents
provider_slug: cloudevents
slug: cloudevents-context
tags:
- Cloud Native
- Events
- Graduated
- Interoperability
- Messaging
- Specification
- JSON-LD
- Linked Data
- Semantic Web
---
