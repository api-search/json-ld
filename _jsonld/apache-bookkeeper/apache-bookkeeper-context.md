---
class_count: 9
classes:
- LedgerList
- LedgerMetadata
- LedgerEntries
- BookieInfo
- BookieList
- ClusterInfo
- BookieState
- GcStatus
- AuditorInfo
context_file: json-ld/apache-bookkeeper-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-bookkeeper/refs/heads/main/json-ld/apache-bookkeeper-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Bookkeeper from Apache BookKeeper.
layout: jsonld
name: Apache Bookkeeper Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: bookkeeper
  uri: https://bookkeeper.apache.org/vocab#
properties:
- container: ''
  name: ledgerId
  type: long
- container: ''
  name: ensembleSize
  type: integer
- container: ''
  name: writeQuorumSize
  type: integer
- container: ''
  name: ackQuorumSize
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: length
  type: long
- container: ''
  name: lastEntryId
  type: long
- container: ''
  name: freeSpace
  type: long
- container: ''
  name: totalSpace
  type: long
- container: ''
  name: auditorElected
  type: boolean
- container: ''
  name: auditorId
  type: string
- container: ''
  name: clusterUnderReplicated
  type: boolean
- container: ''
  name: ledgerReplicationEnabled
  type: boolean
- container: ''
  name: totalBookiesCount
  type: integer
- container: ''
  name: writableBookiesCount
  type: integer
- container: ''
  name: readonlyBookiesCount
  type: integer
- container: ''
  name: unavailableBookiesCount
  type: integer
- container: ''
  name: running
  type: boolean
- container: ''
  name: readOnly
  type: boolean
- container: ''
  name: shuttingDown
  type: boolean
- container: ''
  name: availableForHighPriorityWrites
  type: boolean
- container: ''
  name: is_in_force_gc
  type: string
- container: ''
  name: Auditor
  type: string
property_count: 23
provider_name: Apache BookKeeper
provider_slug: apache-bookkeeper
slug: apache-bookkeeper-context
tags:
- Apache
- Distributed Systems
- Log Storage
- Open Source
- Storage
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
