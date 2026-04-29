---
class_count: 5
classes:
- LeaderLatchState
- ServiceInstance
- NodeData
- DistributedLock
- name
context_file: json-ld/apache-curator-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-ld/apache-curator-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Curator from Apache Curator.
layout: jsonld
name: Apache Curator Context
namespaces:
- prefix: curator
  uri: https://curator.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: acquired
  type: boolean
- container: ''
  name: address
  type: string
- container: ''
  name: aversion
  type: integer
- container: ''
  name: ctime
  type: integer
- container: ''
  name: cversion
  type: integer
- container: ''
  name: czxid
  type: integer
- container: ''
  name: data
  type: string
- container: ''
  name: dataLength
  type: integer
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: ephemeralOwner
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: isLeader
  type: boolean
- container: ''
  name: lockPath
  type: string
- container: ''
  name: mtime
  type: integer
- container: ''
  name: mzxid
  type: integer
- container: ''
  name: numChildren
  type: integer
- container: set
  name: participants
  type: reference
- container: ''
  name: path
  type: string
- container: ''
  name: payload
  type: reference
- container: ''
  name: port
  type: integer
- container: ''
  name: registrationTimeUTC
  type: integer
- container: ''
  name: serviceType
  type: string
- container: ''
  name: sslPort
  type: integer
- container: ''
  name: stat
  type: reference
- container: ''
  name: state
  type: string
- container: ''
  name: threadCount
  type: integer
- container: ''
  name: version
  type: integer
property_count: 27
provider_name: Apache Curator
provider_slug: apache-curator
slug: apache-curator-context
source_filename: apache-curator-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"curator\": \"https://curator.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LeaderLatchState\": \"curator:LeaderLatchState\",\n    \"ServiceInstance\": \"curator:ServiceInstance\",\n    \"NodeData\": \"curator:NodeData\",\n    \"DistributedLock\": \"curator:DistributedLock\",\n    \"acquired\": {\n      \"@id\": \"curator:acquired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"address\": {\n      \"@id\": \"curator:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aversion\": {\n      \"@id\": \"curator:aversion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ctime\": {\n      \"@id\": \"curator:ctime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cversion\": {\n      \"@id\": \"curator:cversion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"czxid\": {\n      \"@id\": \"curator:czxid\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"data\": {\n      \"@id\": \"curator:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataLength\": {\n      \"@id\": \"curator:dataLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"curator:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ephemeralOwner\": {\n      \"@id\": \"curator:ephemeralOwner\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"curator:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isLeader\": {\n      \"@id\": \"curator:isLeader\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lockPath\": {\n      \"@id\": \"curator:lockPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mtime\": {\n      \"@id\": \"curator:mtime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mzxid\": {\n      \"@id\": \"curator:mzxid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"numChildren\": {\n      \"@id\": \"curator:numChildren\",\n    \
  \  \"@type\": \"xsd:integer\"\n    },\n    \"participants\": {\n      \"@id\": \"curator:participants\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"path\": {\n      \"@id\": \"curator:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"curator:payload\",\n      \"@type\": \"@id\"\n    },\n    \"port\": {\n      \"@id\": \"curator:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registrationTimeUTC\": {\n      \"@id\": \"curator:registrationTimeUTC\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serviceType\": {\n      \"@id\": \"curator:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sslPort\": {\n      \"@id\": \"curator:sslPort\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stat\": {\n      \"@id\": \"curator:stat\",\n      \"@type\": \"@id\"\n    },\n    \"state\": {\n      \"@id\": \"curator:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threadCount\": {\n      \"@id\": \"curator:threadCount\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": {\n      \"@id\": \"curator:version\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-curator/refs/heads/main/json-ld/apache-curator-context.jsonld
tags:
- Apache
- Distributed Coordination
- Distributed Systems
- Java
- Maven
- Open Source
- Service Discovery
- ZooKeeper
- JSON-LD
- Linked Data
- Semantic Web
---
