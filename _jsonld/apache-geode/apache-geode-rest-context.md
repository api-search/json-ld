---
class_count: 11
classes:
- RegionInfo
- name
- FunctionResult
- RegionData
- QueryResult
- RegionListResponse
- FunctionListResponse
- KeyListResponse
- ServerListResponse
- QueryInfo
- QueryListResponse
context_file: json-ld/apache-geode-rest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/json-ld/apache-geode-rest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Geode Rest from Apache Geode.
layout: jsonld
name: Apache Geode Rest Context
namespaces:
- prefix: geode
  uri: https://geode.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: keyConstraint
  type: string
- container: ''
  name: valueConstraint
  type: string
- container: ''
  name: result
  type: '@set'
- container: ''
  name: regions
  type: '@set'
- container: ''
  name: functions
  type: '@set'
- container: ''
  name: keys
  type: '@set'
- container: ''
  name: servers
  type: '@set'
- container: ''
  name: id
  type: string
- container: ''
  name: oql
  type: string
- container: ''
  name: queries
  type: '@set'
property_count: 11
provider_name: Apache Geode
provider_slug: apache-geode
slug: apache-geode-rest-context
tags:
- Apache
- Caching
- Data Grid
- Distributed Systems
- In-Memory
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
