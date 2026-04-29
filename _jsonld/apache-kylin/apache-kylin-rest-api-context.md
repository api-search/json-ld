---
api_specs:
- filename: apache-kylin-rest-api.yaml
  format: yaml
  label: Apache Kylin REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/openapi/apache-kylin-rest-api.yaml
class_count: 10
classes:
- AuthResponse
- Table
- Project
- Model
- Job
- ProjectRequest
- QueryRequest
- QueryResponse
- name
- description
context_file: json-ld/apache-kylin-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/json-ld/apache-kylin-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Kylin Rest Api from Apache Kylin.
layout: jsonld
name: Apache Kylin Rest Api Context
namespaces:
- prefix: kylin
  uri: https://apache-kylin.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: userDetails
  type: reference
- container: set
  name: authorities
  type: reference
- container: set
  name: columns
  type: reference
- container: ''
  name: cardinality
  type: reference
- container: ''
  name: exd
  type: reference
- container: ''
  name: createTimeUTC
  type: integer
- container: ''
  name: factTable
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: relatedCube
  type: string
- container: ''
  name: relatedSegment
  type: string
- container: ''
  name: submitTime
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: mrWaiting
  type: integer
- container: ''
  name: sql
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: offset
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: acceptPartial
  type: boolean
- container: set
  name: columnMetas
  type: reference
- container: set
  name: results
  type: string
- container: ''
  name: queryId
  type: string
- container: ''
  name: isException
  type: boolean
- container: ''
  name: exceptionMessage
  type: string
- container: ''
  name: totalScanCount
  type: integer
- container: ''
  name: totalScanBytes
  type: integer
- container: ''
  name: hitExceptionCache
  type: boolean
- container: ''
  name: storageCacheUsed
  type: boolean
property_count: 29
provider_name: Apache Kylin
provider_slug: apache-kylin
slug: apache-kylin-rest-api-context
source_filename: apache-kylin-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kylin\": \"https://apache-kylin.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthResponse\": \"kylin:AuthResponse\",\n    \"Table\": \"kylin:Table\",\n    \"Project\": \"kylin:Project\",\n    \"Model\": \"kylin:Model\",\n    \"Job\": \"kylin:Job\",\n    \"ProjectRequest\": \"kylin:ProjectRequest\",\n    \"QueryRequest\": \"kylin:QueryRequest\",\n    \"QueryResponse\": \"kylin:QueryResponse\",\n    \"userDetails\": {\n      \"@id\": \"kylin:userDetails\",\n      \"@type\": \"@id\"\n    },\n    \"authorities\": {\n      \"@id\": \"kylin:authorities\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"columns\": {\n      \"@id\": \"kylin:columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"cardinality\": {\n     \
  \ \"@id\": \"kylin:cardinality\",\n      \"@type\": \"@id\"\n    },\n    \"exd\": {\n      \"@id\": \"kylin:exd\",\n      \"@type\": \"@id\"\n    },\n    \"description\": \"schema:description\",\n    \"createTimeUTC\": {\n      \"@id\": \"kylin:createTimeUTC\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"factTable\": {\n      \"@id\": \"kylin:factTable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kylin:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"kylin:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"kylin:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedCube\": {\n      \"@id\": \"kylin:relatedCube\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedSegment\": {\n      \"@id\": \"kylin:relatedSegment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submitTime\": {\n      \"@id\": \"kylin:submitTime\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"duration\": {\n      \"@id\": \"kylin:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mrWaiting\": {\n      \"@id\": \"kylin:mrWaiting\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sql\": {\n      \"@id\": \"kylin:sql\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"kylin:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n      \"@id\": \"kylin:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"kylin:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"acceptPartial\": {\n      \"@id\": \"kylin:acceptPartial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"columnMetas\": {\n      \"@id\": \"kylin:columnMetas\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"kylin:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryId\": {\n      \"@id\": \"kylin:queryId\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"isException\": {\n      \"@id\": \"kylin:isException\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exceptionMessage\": {\n      \"@id\": \"kylin:exceptionMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalScanCount\": {\n      \"@id\": \"kylin:totalScanCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalScanBytes\": {\n      \"@id\": \"kylin:totalScanBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hitExceptionCache\": {\n      \"@id\": \"kylin:hitExceptionCache\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"storageCacheUsed\": {\n      \"@id\": \"kylin:storageCacheUsed\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/json-ld/apache-kylin-rest-api-context.jsonld
tags:
- Analytics
- Big Data
- Cube
- OLAP
- Open Source
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
