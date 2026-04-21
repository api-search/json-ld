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
