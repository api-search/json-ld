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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"geode\": \"https://geode.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RegionInfo\": \"geode:RegionInfo\",\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"geode:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyConstraint\": {\n      \"@id\": \"geode:keyConstraint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueConstraint\": {\n      \"@id\": \"geode:valueConstraint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FunctionResult\": \"geode:FunctionResult\",\n    \"result\": {\n      \"@id\": \"geode:result\",\n      \"@type\": \"@set\"\n    },\n    \"RegionData\": \"geode:RegionData\",\n    \"QueryResult\": \"geode:QueryResult\",\n    \"RegionListResponse\": \"geode:RegionListResponse\",\n    \"regions\": {\n      \"@id\": \"geode:regions\",\n      \"@type\": \"\
  @set\"\n    },\n    \"FunctionListResponse\": \"geode:FunctionListResponse\",\n    \"functions\": {\n      \"@id\": \"geode:functions\",\n      \"@type\": \"@set\"\n    },\n    \"KeyListResponse\": \"geode:KeyListResponse\",\n    \"keys\": {\n      \"@id\": \"geode:keys\",\n      \"@type\": \"@set\"\n    },\n    \"ServerListResponse\": \"geode:ServerListResponse\",\n    \"servers\": {\n      \"@id\": \"geode:servers\",\n      \"@type\": \"@set\"\n    },\n    \"QueryInfo\": \"geode:QueryInfo\",\n    \"id\": {\n      \"@id\": \"geode:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oql\": {\n      \"@id\": \"geode:oql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueryListResponse\": \"geode:QueryListResponse\",\n    \"queries\": {\n      \"@id\": \"geode:queries\",\n      \"@type\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-geode/refs/heads/main/json-ld/apache-geode-rest-context.jsonld
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
