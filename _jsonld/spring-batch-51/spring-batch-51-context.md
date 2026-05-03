---
api_specs:
- filename: spring-batch-51-openapi.yml
  format: yaml
  label: Spring Batch 5.1 Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-batch-51/refs/heads/main/openapi/spring-batch-51-openapi.yml
class_count: 6
classes:
- JobExecution
- JobInstance
- StepExecution
- ExecutionContext
- JobParameters
- JobParameter
context_file: json-ld/spring-batch-51-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-batch-51/refs/heads/main/json-ld/spring-batch-51-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Batch 51 from Spring Batch 5.1.
layout: jsonld
name: Spring Batch 51 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: batch
  uri: https://spring.io/batch/5.1/
properties:
- container: ''
  name: id
  type: long
- container: ''
  name: jobName
  type: string
- container: ''
  name: jobId
  type: long
- container: ''
  name: stepName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: exitCode
  type: string
- container: ''
  name: exitDescription
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: readCount
  type: integer
- container: ''
  name: writeCount
  type: integer
- container: ''
  name: commitCount
  type: integer
- container: ''
  name: rollbackCount
  type: integer
- container: ''
  name: readSkipCount
  type: integer
- container: ''
  name: processSkipCount
  type: integer
- container: ''
  name: writeSkipCount
  type: integer
- container: ''
  name: filterCount
  type: integer
- container: ''
  name: jobParameters
  type: reference
- container: set
  name: stepExecutions
  type: reference
- container: ''
  name: executionContext
  type: reference
- container: ''
  name: version
  type: integer
- container: ''
  name: identifying
  type: boolean
- container: ''
  name: parameterType
  type: string
property_count: 25
provider_name: Spring Batch 5.1
provider_slug: spring-batch-51
slug: spring-batch-51-context
source_filename: spring-batch-51-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://spring.io/batch/5.1/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"batch\": \"https://spring.io/batch/5.1/\",\n\n    \"JobExecution\": \"batch:JobExecution\",\n    \"JobInstance\": \"batch:JobInstance\",\n    \"StepExecution\": \"batch:StepExecution\",\n    \"ExecutionContext\": \"batch:ExecutionContext\",\n    \"JobParameters\": \"batch:JobParameters\",\n    \"JobParameter\": \"batch:JobParameter\",\n\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:long\" },\n    \"jobName\": { \"@id\": \"batch:jobName\", \"@type\": \"xsd:string\" },\n    \"jobId\": { \"@id\": \"batch:jobId\", \"@type\": \"xsd:long\" },\n    \"stepName\": { \"@id\": \"batch:stepName\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"batch:status\", \"@type\": \"xsd:string\" },\n    \"exitCode\": { \"@id\": \"batch:exitCode\", \"@type\": \"xsd:string\" },\n    \"exitDescription\"\
  : { \"@id\": \"batch:exitDescription\", \"@type\": \"xsd:string\" },\n\n    \"startTime\": { \"@id\": \"batch:startTime\", \"@type\": \"xsd:dateTime\" },\n    \"endTime\": { \"@id\": \"batch:endTime\", \"@type\": \"xsd:dateTime\" },\n    \"createTime\": { \"@id\": \"batch:createTime\", \"@type\": \"xsd:dateTime\" },\n    \"lastUpdated\": { \"@id\": \"batch:lastUpdated\", \"@type\": \"xsd:dateTime\" },\n\n    \"readCount\": { \"@id\": \"batch:readCount\", \"@type\": \"xsd:integer\" },\n    \"writeCount\": { \"@id\": \"batch:writeCount\", \"@type\": \"xsd:integer\" },\n    \"commitCount\": { \"@id\": \"batch:commitCount\", \"@type\": \"xsd:integer\" },\n    \"rollbackCount\": { \"@id\": \"batch:rollbackCount\", \"@type\": \"xsd:integer\" },\n    \"readSkipCount\": { \"@id\": \"batch:readSkipCount\", \"@type\": \"xsd:integer\" },\n    \"processSkipCount\": { \"@id\": \"batch:processSkipCount\", \"@type\": \"xsd:integer\" },\n    \"writeSkipCount\": { \"@id\": \"batch:writeSkipCount\", \"\
  @type\": \"xsd:integer\" },\n    \"filterCount\": { \"@id\": \"batch:filterCount\", \"@type\": \"xsd:integer\" },\n\n    \"jobParameters\": { \"@id\": \"batch:jobParameters\", \"@type\": \"@id\" },\n    \"stepExecutions\": { \"@id\": \"batch:stepExecutions\", \"@type\": \"@id\", \"@container\": \"@set\" },\n    \"executionContext\": { \"@id\": \"batch:executionContext\", \"@type\": \"@id\" },\n\n    \"version\": { \"@id\": \"batch:version\", \"@type\": \"xsd:integer\" },\n    \"identifying\": { \"@id\": \"batch:identifying\", \"@type\": \"xsd:boolean\" },\n    \"parameterType\": { \"@id\": \"batch:parameterType\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-batch-51/refs/heads/main/json-ld/spring-batch-51-context.jsonld
tags:
- Batch Processing
- Data Processing
- Enterprise
- ETL
- Java
- Job Scheduling
- Spring Framework
- JSON-LD
- Linked Data
- Semantic Web
---
