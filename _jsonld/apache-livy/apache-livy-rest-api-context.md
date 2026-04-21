---
class_count: 12
classes:
- StatementList
- CreateSessionRequest
- Log
- StatementRequest
- BatchState
- BatchList
- CreateBatchRequest
- Batch
- Session
- Statement
- SessionList
- SessionState
context_file: json-ld/apache-livy-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/json-ld/apache-livy-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Livy Rest Api from Apache Livy.
layout: jsonld
name: Apache Livy Rest Api Context
namespaces:
- prefix: livy
  uri: https://apache-livy.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: totalStatements
  type: integer
- container: set
  name: statements
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: proxyUser
  type: string
- container: set
  name: jars
  type: string
- container: set
  name: pyFiles
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: driverMemory
  type: string
- container: ''
  name: driverCores
  type: integer
- container: ''
  name: executorMemory
  type: string
- container: ''
  name: executorCores
  type: integer
- container: ''
  name: numExecutors
  type: integer
- container: ''
  name: conf
  type: reference
- container: ''
  name: id
  type: integer
- container: ''
  name: from
  type: integer
- container: ''
  name: size
  type: integer
- container: set
  name: log
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: total
  type: integer
- container: set
  name: sessions
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: className
  type: string
- container: set
  name: args
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: appInfo
  type: reference
- container: ''
  name: owner
  type: string
- container: ''
  name: output
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: executionCount
  type: integer
- container: ''
  name: data
  type: reference
property_count: 31
provider_name: Apache Livy
provider_slug: apache-livy
slug: apache-livy-rest-api-context
tags:
- Big Data
- Interactive Computing
- Open Source
- REST
- Spark
- JSON-LD
- Linked Data
- Semantic Web
---
