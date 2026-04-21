---
class_count: 9
classes:
- BundleList
- Bundle
- BundleStateRequest
- RouteList
- Route
- EndpointList
- Endpoint
- QueueList
- Queue
context_file: json-ld/apache-servicemix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/json-ld/apache-servicemix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Servicemix from Apache ServiceMix.
layout: jsonld
name: Apache Servicemix Context
namespaces:
- prefix: serv
  uri: https://servicemix.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: bundles
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: schema:name
- container: ''
  name: symbolicName
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: location
  type: string
- container: set
  name: routes
  type: ''
- container: ''
  name: description
  type: schema:description
- container: ''
  name: status
  type: string
- container: ''
  name: uptime
  type: string
- container: ''
  name: exchangesTotal
  type: integer
- container: ''
  name: exchangesFailed
  type: integer
- container: ''
  name: meanProcessingTime
  type: integer
- container: set
  name: endpoints
  type: ''
- container: ''
  name: address
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: wsdl
  type: string
- container: set
  name: queues
  type: ''
- container: ''
  name: pendingQueueSize
  type: integer
- container: ''
  name: consumerCount
  type: integer
- container: ''
  name: enqueueCount
  type: integer
- container: ''
  name: dequeueCount
  type: integer
property_count: 24
provider_name: Apache ServiceMix
provider_slug: apache-servicemix
slug: apache-servicemix-context
tags:
- Enterprise Integration
- ESB
- Integration
- Messaging
- OSGi
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
