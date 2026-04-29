---
class_count: 3
classes:
- AggregationQuery
- AggregationResponse
- TenantSummary
context_file: json-ld/palo-alto-sase-aggregate-monitoring-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-aggregate-monitoring-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Aggregate Monitoring Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Aggregate Monitoring Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: childCount
  type: integer
- container: ''
  name: count
  type: integer
- container: set
  name: data
  type: reference
- container: ''
  name: depth
  type: integer
- container: ''
  name: displayName
  type: string
- container: ''
  name: end
  type: dateTime
- container: ''
  name: field
  type: string
- container: ''
  name: filter
  type: reference
- container: set
  name: groupBy
  type: string
- container: ''
  name: histogram
  type: reference
- container: ''
  name: interval
  type: string
- container: ''
  name: last
  type: string
- container: ''
  name: order
  type: string
- container: ''
  name: parentId
  type: string
- container: set
  name: sort
  type: reference
- container: ''
  name: start
  type: dateTime
- container: ''
  name: timeRange
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: total
  type: integer
- container: ''
  name: tsgId
  type: string
- container: ''
  name: values
  type: reference
property_count: 21
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-aggregate-monitoring-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AggregationQuery\": \"pan:AggregationQuery\",\n    \"AggregationResponse\": \"pan:AggregationResponse\",\n    \"TenantSummary\": \"pan:TenantSummary\",\n    \"childCount\": {\n      \"@id\": \"pan:child_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"depth\": {\n      \"@id\": \"pan:depth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"pan:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"\
  field\": {\n      \"@id\": \"pan:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"@id\"\n    },\n    \"groupBy\": {\n      \"@id\": \"pan:group_by\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"histogram\": {\n      \"@id\": \"pan:histogram\",\n      \"@type\": \"@id\"\n    },\n    \"interval\": {\n      \"@id\": \"pan:interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last\": {\n      \"@id\": \"pan:last\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"pan:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"pan:parent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sort\": {\n      \"@id\": \"pan:sort\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"start\": {\n      \"@id\": \"pan:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeRange\": {\n      \"@id\"\
  : \"pan:time_range\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsg_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"pan:values\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-aggregate-monitoring-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
