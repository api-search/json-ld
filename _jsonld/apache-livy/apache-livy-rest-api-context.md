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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"livy\": \"https://apache-livy.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StatementList\": \"livy:StatementList\",\n    \"CreateSessionRequest\": \"livy:CreateSessionRequest\",\n    \"Log\": \"livy:Log\",\n    \"StatementRequest\": \"livy:StatementRequest\",\n    \"BatchState\": \"livy:BatchState\",\n    \"BatchList\": \"livy:BatchList\",\n    \"CreateBatchRequest\": \"livy:CreateBatchRequest\",\n    \"Batch\": \"livy:Batch\",\n    \"Session\": \"livy:Session\",\n    \"Statement\": \"livy:Statement\",\n    \"SessionList\": \"livy:SessionList\",\n    \"SessionState\": \"livy:SessionState\",\n    \"totalStatements\": {\n      \"@id\": \"livy:total_statements\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"statements\": {\n      \"@id\": \"livy:statements\",\n      \"@container\": \"@set\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"livy:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"proxyUser\": {\n      \"@id\": \"livy:proxyUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jars\": {\n      \"@id\": \"livy:jars\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pyFiles\": {\n      \"@id\": \"livy:pyFiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"livy:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"driverMemory\": {\n      \"@id\": \"livy:driverMemory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"driverCores\": {\n      \"@id\": \"livy:driverCores\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"executorMemory\": {\n      \"@id\": \"livy:executorMemory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executorCores\": {\n      \"@id\": \"livy:executorCores\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"numExecutors\": {\n      \"@id\": \"livy:numExecutors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"conf\": {\n      \"@id\": \"livy:conf\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"livy:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"from\": {\n      \"@id\": \"livy:from\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"size\": {\n      \"@id\": \"livy:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"log\": {\n      \"@id\": \"livy:log\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"livy:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"livy:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"livy:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sessions\": {\n      \"@id\": \"livy:sessions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"file\": {\n      \"@id\": \"livy:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"className\": {\n      \"@id\": \"livy:className\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"livy:args\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"livy:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appInfo\": {\n      \"@id\": \"livy:appInfo\",\n      \"@type\": \"@id\"\n    },\n    \"owner\": {\n      \"@id\": \"livy:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"livy:output\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"livy:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionCount\": {\n      \"@id\": \"livy:execution_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"livy:data\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-livy/refs/heads/main/json-ld/apache-livy-rest-api-context.jsonld
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
