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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"serv\": \"https://servicemix.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BundleList\": \"serv:BundleList\",\n    \"Bundle\": \"serv:Bundle\",\n    \"BundleStateRequest\": \"serv:BundleStateRequest\",\n    \"RouteList\": \"serv:RouteList\",\n    \"Route\": \"serv:Route\",\n    \"EndpointList\": \"serv:EndpointList\",\n    \"Endpoint\": \"serv:Endpoint\",\n    \"QueueList\": \"serv:QueueList\",\n    \"Queue\": \"serv:Queue\",\n    \"bundles\": {\n      \"@id\": \"serv:bundles\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"serv:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"serv:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"serv:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"symbolicName\": {\n      \"@id\": \"serv:symbolicName\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"serv:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"serv:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"serv:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routes\": {\n      \"@id\": \"serv:routes\",\n      \"@container\": \"@set\"\n    },\n    \"description\": {\n      \"@id\": \"serv:description\",\n      \"@type\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"serv:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uptime\": {\n      \"@id\": \"serv:uptime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchangesTotal\": {\n      \"@id\": \"serv:exchangesTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exchangesFailed\": {\n      \"@id\": \"serv:exchangesFailed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"meanProcessingTime\": {\n      \"@id\": \"serv:meanProcessingTime\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"endpoints\": {\n      \"@id\": \"serv:endpoints\",\n      \"@container\": \"@set\"\n    },\n    \"address\": {\n      \"@id\": \"serv:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"serv:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wsdl\": {\n      \"@id\": \"serv:wsdl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queues\": {\n      \"@id\": \"serv:queues\",\n      \"@container\": \"@set\"\n    },\n    \"pendingQueueSize\": {\n      \"@id\": \"serv:pendingQueueSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"consumerCount\": {\n      \"@id\": \"serv:consumerCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enqueueCount\": {\n      \"@id\": \"serv:enqueueCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dequeueCount\": {\n      \"@id\": \"serv:dequeueCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/json-ld/apache-servicemix-context.jsonld
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
