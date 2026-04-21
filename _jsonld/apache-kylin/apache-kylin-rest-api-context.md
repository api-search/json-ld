---
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
