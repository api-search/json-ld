---
api_specs:
- filename: apache-pig-api.yaml
  format: yaml
  label: Apache Pig
  slug: apache-pig
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/openapi/apache-pig-api.yaml
class_count: 7
classes:
- JobList
- Job
- JobRequest
- JobLogs
- ScriptRequest
- ValidationResult
- ValidationError
context_file: json-ld/apache-pig-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/json-ld/apache-pig-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Pig from Apache Pig.
layout: jsonld
name: Apache Pig Context
namespaces:
- prefix: pig
  uri: https://pig.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: jobs
  type: ''
- container: ''
  name: total
  type: integer
- container: ''
  name: jobId
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: status
  type: string
- container: ''
  name: submittedAt
  type: string
- container: ''
  name: startedAt
  type: string
- container: ''
  name: completedAt
  type: string
- container: ''
  name: executionEngine
  type: string
- container: ''
  name: progress
  type: decimal
- container: ''
  name: script
  type: string
- container: ''
  name: parameters
  type: string
- container: set
  name: logs
  type: ''
- container: ''
  name: valid
  type: boolean
- container: set
  name: errors
  type: ''
- container: ''
  name: line
  type: integer
- container: ''
  name: column
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: severity
  type: string
property_count: 19
provider_name: Apache Pig
provider_slug: apache-pig
slug: apache-pig-context
source_filename: apache-pig-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pig\": \"https://pig.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"JobList\": \"pig:JobList\",\n    \"Job\": \"pig:Job\",\n    \"JobRequest\": \"pig:JobRequest\",\n    \"JobLogs\": \"pig:JobLogs\",\n    \"ScriptRequest\": \"pig:ScriptRequest\",\n    \"ValidationResult\": \"pig:ValidationResult\",\n    \"ValidationError\": \"pig:ValidationError\",\n    \"jobs\": {\n      \"@id\": \"pig:jobs\",\n      \"@container\": \"@set\"\n    },\n    \"total\": {\n      \"@id\": \"pig:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jobId\": {\n      \"@id\": \"pig:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"pig:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"status\": {\n      \"@id\": \"pig:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"pig:submittedAt\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"pig:startedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"pig:completedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionEngine\": {\n      \"@id\": \"pig:executionEngine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\": {\n      \"@id\": \"pig:progress\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"script\": {\n      \"@id\": \"pig:script\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"pig:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logs\": {\n      \"@id\": \"pig:logs\",\n      \"@container\": \"@set\"\n    },\n    \"valid\": {\n      \"@id\": \"pig:valid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"errors\": {\n      \"@id\": \"pig:errors\",\n      \"@container\": \"@set\"\n    },\n    \"line\": {\n      \"@id\": \"pig:line\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"column\": {\n      \"@id\": \"pig:column\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"pig:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pig:severity\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/json-ld/apache-pig-context.jsonld
tags:
- Big Data
- Data Analysis
- ETL
- Hadoop
- Scripting
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
