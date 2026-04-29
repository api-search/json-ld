---
class_count: 7
classes:
- CustomQuery
- DataResourceQuery
- DataResourceResponse
- ExportJobResponse
- ExportJobStatus
- QueryFilter
- TimeRange
context_file: json-ld/palo-alto-prisma-access-insights-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-insights-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Access Insights Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Access Insights Api Context
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
  name: count
  type: integer
- container: set
  name: data
  type: reference
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: enabledGranularity
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: filter
  type: reference
- container: ''
  name: from
  type: dateTime
- container: set
  name: groupBy
  type: string
- container: ''
  name: header
  type: reference
- container: ''
  name: histogram
  type: reference
- container: ''
  name: jobId
  type: string
- container: ''
  name: last
  type: reference
- container: ''
  name: limit
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: operator
  type: string
- container: ''
  name: order
  type: string
- container: ''
  name: pagination
  type: reference
- container: ''
  name: properties
  type: reference
- container: ''
  name: property
  type: string
- container: ''
  name: query
  type: reference
- container: ''
  name: requestId
  type: string
- container: ''
  name: resource
  type: string
- container: set
  name: rules
  type: reference
- container: ''
  name: sort
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: timeRange
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: to
  type: dateTime
- container: ''
  name: type
  type: string
- container: ''
  name: units
  type: string
- container: ''
  name: value
  type: reference
- container: set
  name: values
  type: string
property_count: 34
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-access-insights-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomQuery\": \"pan:CustomQuery\",\n    \"DataResourceQuery\": \"pan:DataResourceQuery\",\n    \"DataResourceResponse\": \"pan:DataResourceResponse\",\n    \"ExportJobResponse\": \"pan:ExportJobResponse\",\n    \"ExportJobStatus\": \"pan:ExportJobStatus\",\n    \"QueryFilter\": \"pan:QueryFilter\",\n    \"TimeRange\": \"pan:TimeRange\",\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"pan:download_url\",\n      \"@type\": \"@id\"\n    },\n    \"enabledGranularity\": {\n      \"@id\": \"pan:enabledGranularity\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"pan:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"@id\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"groupBy\": {\n      \"@id\": \"pan:group_by\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"header\": {\n      \"@id\": \"pan:header\",\n      \"@type\": \"@id\"\n    },\n    \"histogram\": {\n      \"@id\": \"pan:histogram\",\n      \"@type\": \"@id\"\n    },\n    \"jobId\": {\n      \"@id\": \"pan:job_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last\": {\n      \"@id\": \"pan:last\",\n      \"@type\": \"@id\"\n    },\n    \"limit\": {\n      \"@id\": \"pan:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"pan:offset\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"pan:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"pan:pagination\",\n      \"@type\": \"@id\"\n    },\n    \"properties\": {\n      \"@id\": \"pan:properties\",\n      \"@type\": \"@id\"\n    },\n    \"property\": {\n      \"@id\": \"pan:property\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"pan:query\",\n      \"@type\": \"@id\"\n    },\n    \"requestId\": {\n      \"@id\": \"pan:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"pan:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"pan:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sort\": {\n      \"@id\": \"pan:sort\",\n      \"@type\": \"@id\"\n    },\n    \"status\"\
  : {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"pan:submitted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeRange\": {\n      \"@id\": \"pan:time_range\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"pan:units\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"@id\"\n    },\n    \"values\": {\n      \"@id\": \"pan:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-access-insights-api-context.jsonld
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
