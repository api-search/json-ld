---
api_specs:
- filename: apache-bookkeeper-admin-openapi.yaml
  format: yaml
  label: Apache BookKeeper Admin API
  slug: apache-bookkeeper-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-bookkeeper/refs/heads/main/openapi/apache-bookkeeper-admin-openapi.yaml
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
source_filename: apache-bookkeeper-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"bookkeeper\": \"https://bookkeeper.apache.org/vocab#\",\n    \"LedgerList\": \"bookkeeper:LedgerList\",\n    \"LedgerMetadata\": \"bookkeeper:LedgerMetadata\",\n    \"LedgerEntries\": \"bookkeeper:LedgerEntries\",\n    \"BookieInfo\": \"bookkeeper:BookieInfo\",\n    \"BookieList\": \"bookkeeper:BookieList\",\n    \"ClusterInfo\": \"bookkeeper:ClusterInfo\",\n    \"BookieState\": \"bookkeeper:BookieState\",\n    \"GcStatus\": \"bookkeeper:GcStatus\",\n    \"AuditorInfo\": \"bookkeeper:AuditorInfo\",\n    \"ledgerId\": { \"@id\": \"bookkeeper:ledgerId\", \"@type\": \"xsd:long\" },\n    \"ensembleSize\": { \"@id\": \"bookkeeper:ensembleSize\", \"@type\": \"xsd:integer\" },\n    \"writeQuorumSize\": { \"@id\": \"bookkeeper:writeQuorumSize\", \"@type\": \"xsd:integer\" },\n    \"ackQuorumSize\"\
  : { \"@id\": \"bookkeeper:ackQuorumSize\", \"@type\": \"xsd:integer\" },\n    \"state\": { \"@id\": \"bookkeeper:state\", \"@type\": \"xsd:string\" },\n    \"length\": { \"@id\": \"bookkeeper:length\", \"@type\": \"xsd:long\" },\n    \"lastEntryId\": { \"@id\": \"bookkeeper:lastEntryId\", \"@type\": \"xsd:long\" },\n    \"freeSpace\": { \"@id\": \"bookkeeper:freeSpace\", \"@type\": \"xsd:long\" },\n    \"totalSpace\": { \"@id\": \"bookkeeper:totalSpace\", \"@type\": \"xsd:long\" },\n    \"auditorElected\": { \"@id\": \"bookkeeper:auditorElected\", \"@type\": \"xsd:boolean\" },\n    \"auditorId\": { \"@id\": \"bookkeeper:auditorId\", \"@type\": \"xsd:string\" },\n    \"clusterUnderReplicated\": { \"@id\": \"bookkeeper:clusterUnderReplicated\", \"@type\": \"xsd:boolean\" },\n    \"ledgerReplicationEnabled\": { \"@id\": \"bookkeeper:ledgerReplicationEnabled\", \"@type\": \"xsd:boolean\" },\n    \"totalBookiesCount\": { \"@id\": \"bookkeeper:totalBookiesCount\", \"@type\": \"xsd:integer\"\
  \ },\n    \"writableBookiesCount\": { \"@id\": \"bookkeeper:writableBookiesCount\", \"@type\": \"xsd:integer\" },\n    \"readonlyBookiesCount\": { \"@id\": \"bookkeeper:readonlyBookiesCount\", \"@type\": \"xsd:integer\" },\n    \"unavailableBookiesCount\": { \"@id\": \"bookkeeper:unavailableBookiesCount\", \"@type\": \"xsd:integer\" },\n    \"running\": { \"@id\": \"bookkeeper:running\", \"@type\": \"xsd:boolean\" },\n    \"readOnly\": { \"@id\": \"bookkeeper:readOnly\", \"@type\": \"xsd:boolean\" },\n    \"shuttingDown\": { \"@id\": \"bookkeeper:shuttingDown\", \"@type\": \"xsd:boolean\" },\n    \"availableForHighPriorityWrites\": { \"@id\": \"bookkeeper:availableForHighPriorityWrites\", \"@type\": \"xsd:boolean\" },\n    \"is_in_force_gc\": { \"@id\": \"bookkeeper:is_in_force_gc\", \"@type\": \"xsd:string\" },\n    \"Auditor\": { \"@id\": \"bookkeeper:Auditor\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-bookkeeper/refs/heads/main/json-ld/apache-bookkeeper-context.jsonld
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
