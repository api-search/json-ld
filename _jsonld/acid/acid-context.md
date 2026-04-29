---
class_count: 2
classes:
- AcidSagaStep
- AcidTransaction
context_file: json-ld/acid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/json-ld/acid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acid from ACID.
layout: jsonld
name: Acid Context
namespaces:
- prefix: acid
  uri: https://acid.example.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: compensationEndpoint
  type: reference
- container: ''
  name: durationMs
  type: integer
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: executionTimeMs
  type: decimal
- container: ''
  name: isolationLevel
  type: string
- container: ''
  name: operationId
  type: integer
- container: set
  name: operations
  type: string
- container: ''
  name: retryCount
  type: integer
- container: ''
  name: rollbackReason
  type: string
- container: ''
  name: rowsAffected
  type: integer
- container: ''
  name: sagaId
  type: string
- container: set
  name: savepoints
  type: string
- container: ''
  name: sequence
  type: integer
- container: ''
  name: serviceEndpoint
  type: reference
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: stepId
  type: string
- container: ''
  name: stepName
  type: string
- container: ''
  name: table
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: type
  type: string
property_count: 22
provider_name: ACID
provider_slug: acid
slug: acid-context
source_filename: acid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acid\": \"https://acid.example.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcidSagaStep\": \"acid:AcidSagaStep\",\n    \"AcidTransaction\": \"acid:AcidTransaction\",\n    \"compensationEndpoint\": {\n      \"@id\": \"acid:compensationEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"durationMs\": {\n      \"@id\": \"acid:durationMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"acid:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"acid:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionTimeMs\": {\n      \"@id\": \"acid:executionTimeMs\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isolationLevel\": {\n      \"@id\": \"acid:isolationLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationId\"\
  : {\n      \"@id\": \"acid:operationId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"operations\": {\n      \"@id\": \"acid:operations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryCount\": {\n      \"@id\": \"acid:retryCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rollbackReason\": {\n      \"@id\": \"acid:rollbackReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowsAffected\": {\n      \"@id\": \"acid:rowsAffected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sagaId\": {\n      \"@id\": \"acid:sagaId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"savepoints\": {\n      \"@id\": \"acid:savepoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequence\": {\n      \"@id\": \"acid:sequence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serviceEndpoint\": {\n      \"@id\": \"acid:serviceEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"startTime\": {\n      \"@id\"\
  : \"acid:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"acid:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepId\": {\n      \"@id\": \"acid:stepId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepName\": {\n      \"@id\": \"acid:stepName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table\": {\n      \"@id\": \"acid:table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"acid:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"acid:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acid/refs/heads/main/json-ld/acid-context.jsonld
tags:
- ACID
- Database
- Transactions
- Atomicity
- Consistency
- Isolation
- Durability
- Distributed Systems
- JSON-LD
- Linked Data
- Semantic Web
---
